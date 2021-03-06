---
title: Configurar la suplantación
manager: sethgros
ms.date: 11/16/2014
ms.audience: Developer
ms.assetid: efcef39f-e26d-4eed-95ac-36a5bf8c089f
description: Aprenda a otorgar el rol de suplantación a una cuenta de servicio usando el Shell de administración de Exchange.
localization_priority: Priority
ms.openlocfilehash: f8fe95536213e347840af082d765a9cc2fbce819
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/31/2020
ms.locfileid: "44455901"
---
# <a name="configure-impersonation"></a>Configurar la suplantación

Aprenda a otorgar el rol de suplantación a una cuenta de servicio usando el Shell de administración de Exchange. 
  
La suplantación permite que un llamador, como una aplicación de servicio, suplante una cuenta de usuario. El llamador puede realizar operaciones usando los permisos asociados a la cuenta de suplantación en lugar de los permisos asociados con la cuenta del llamador.
  
Exchange Online, Exchange Online como parte de Office 365 y las versiones de Exchange a partir de Exchange 2013 usan el control de acceso basado en roles (RBAC) para asignar permisos a las cuentas. El administrador del servidor Exchange deberá conceder a la cuenta de servicio que suplantará a otros usuarios el rol **ApplicationImpersonation** usando el cmdlet [New-ManagementRoleAssignment](https://msdn.microsoft.com/library/34d4f2e3-f2c5-49e1-a6a9-1366da65a78c.aspx). 
  
## <a name="configuring-the-applicationimpersonation-role"></a>Configurar el rol ApplicationImpersonation

Cuando usted o el administrador del servidor Exchanger asigne el rol **ApplicationImpersonation**, use los parámetros siguientes del cmdlet **New-ManagementRoleAssignment**: 
  
-  _Name_: el nombre descriptivo de la asignación de roles. Cada vez que asigna un rol, se realiza una entrada en la lista de roles RBAC. Puede comprobar las asignaciones de funciones con el cmdlet [Get-ManagementRoleAssignment](https://msdn.microsoft.com/library/a3a6ee46-061b-444a-8639-43a416309445.aspx). 
    
-  _Role_: el rol RBAC para asignar. Al configurar la suplantación, se asigna el rol **ApplicationImpersonation**. 
    
-  _User_: la cuenta de servicio. 
    
-  _CustomRecipientScope_: el ámbito de los usuarios que puede suplantar la cuenta de servicio. La cuenta de servicio solo tendrá permitido suplantar a otros usuarios dentro del ámbito especificado. Si no se especifica ningún ámbito, la cuenta de servicio tiene el rol **ApplicationImpersonation** sobre todos los usuarios de una organización. Puede crear ámbitos de administración personalizada usando el cmdlet [New-ManagementScope](https://msdn.microsoft.com/library/1ea1f474-69d6-48c0-9beb-bfa4442c5dab.aspx). 
    
Antes de configurar la suplantación, necesita:
  
- Credenciales administrativas para el servidor Exchange.
    
- Credenciales de administrador de dominio u otras credenciales con permiso para crear y asignar roles y ámbitos.
    
- Herramientas de administración de Exchange. Están instaladas en el equipo desde el que se ejecutan los comandos.
    
### <a name="to-configure-impersonation-for-all-users-in-an-organization"></a>Para configurar la suplantación para todos los usuarios de una organización

1. Abra el Shell de administración de Exchange. En el menú Inicio, elija **Todos los programas** > **Microsoft Exchange Server 2013**. 
    
2. Ejecute el cmdlet **New-ManagementRoleAssignment** para agregar el permiso de suplantación en el usuario especificado. En el ejemplo siguiente se muestra cómo configurar la suplantación para permitir que una cuenta de servicio suplante a los demás usuarios de una organización. 
    
   ```powershell
   New-ManagementRoleAssignment -name:impersonationAssignmentName -Role:ApplicationImpersonation -User:serviceAccount 
   ```

### <a name="to-configure-impersonation-for-specific-users-or-groups-of-users"></a>Para configurar la suplantación de usuarios o grupos de usuarios específicos

1. Abra el Shell de administración de Exchange. En el menú Inicio, elija **Todos los programas** > **Microsoft Exchange Server 2013**. 
    
2. Ejecute el cmdlet **New-ManagementScope** para crear un ámbito al que se pueda asignar el rol de suplantación. Si hay un ámbito existente, puede omitir este paso. En el ejemplo siguiente se muestra cómo crear un ámbito de administración para un grupo específico. 
    
   ```powershell
    New-ManagementScope -Name:scopeName -RecipientRestrictionFilter:recipientFilter
   ```

   El parámetro _RecipientRestrictionFilter_ del cmdlet **New-ManagementScope** define los miembros del ámbito. Puede usar las propiedades del objeto **Identity** para crear el filtro. El siguiente ejemplo es un filtro que restringe el resultado a un solo usuario con el usuario nombre de usuario "john". 
    
   ```powershell
   Name -eq "john"
   ```

3. Ejecute el cmdlet **New-ManagementRoleAssignment** para agregar el permiso para suplantar a los miembros del ámbito especificado. El ejemplo siguiente muestra cómo configurar una cuenta de servicio para suplantar a todos los usuarios de un ámbito. 
    
   ```powershell
    New-ManagementRoleAssignment -Name:impersonationAssignmentName -Role:ApplicationImpersonation -User:serviceAccount -CustomRecipientWriteScope:scopeName
    
   ```


Después de que el administrador conceda los permisos de suplantación, puede usar la cuenta de servicio para realizar llamadas con las cuentas de otros usuarios. Puede comprobar las asignaciones de roles mediante el cmdlet [Get-ManagementRoleAssignment](https://msdn.microsoft.com/library/a3a6ee46-061b-444a-8639-43a416309445.aspx). 
  
## <a name="see-also"></a>Vea también

- [Suplantación y EWS en Exchange](impersonation-and-ews-in-exchange.md)
- [Rol ApplicationImpersonation](https://technet.microsoft.com/library/dd776119%28v=exchg.150%29.aspx)   
- [New-ManagementRoleAssignment](https://msdn.microsoft.com/library/34d4f2e3-f2c5-49e1-a6a9-1366da65a78c.aspx)    
- [Get-ManagementRoleAssignment](https://msdn.microsoft.com/library/a3a6ee46-061b-444a-8639-43a416309445.aspx)
    

