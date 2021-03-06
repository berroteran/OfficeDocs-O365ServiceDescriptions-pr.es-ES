---
title: Administración de destinatarios, dominios e información de la compañía
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) ofrece varias formas de administrar los destinatario, el dominio y la información de la compañía. Como administrador, puede realizar algunas tareas de administración en el centro de administración de Exchange (EAC) y compruebe otras tareas de administración que se realizan en el centro de administración de Microsoft Office 365.
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037085"
---
# <a name="recipient-domain-and-company-management"></a>Administración de destinatarios, dominios e información de la compañía

Microsoft Exchange Online Protection (EOP) ofrece varias formas de administrar los destinatario, el dominio y la información de la compañía. Como administrador, puede realizar algunas tareas de administración en el centro de administración de Exchange (EAC) y compruebe otras tareas de administración que se realizan en el centro de administración de Microsoft Office 365.
  
¿Busca información sobre todas las características de EOP? Vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Destinatarios de correo
<a name="BKMK_mailrecipients"> </a>

Los destinatarios de correo se clasifican como grupos o usuarios de correo y se pueden administrar mediante la sincronización de directorios, directamente en el EAC o mediante el modo remoto de Windows PowerShell. Si va a administrar los destinatarios localmente, debe ejecutar la sincronización de directorios para que los destinatarios de correo se reflejen en el EAC. Los usuarios administrados exclusivamente en el Centro de administración de Office 365 no están disponibles en el EAC, pero se puede agregar o quitar su pertenencia en un grupo de roles de administrador en el EAC. Para más información sobre los destinatarios en EOP, vea [Administrar destinatarios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Permisos de grupo de roles administrativos
<a name="BKMK_adminrolegrouppermissions"> </a>

En EOP, solo puede configurar roles administrativos. Puede agregar y quitar usuarios de los grupos de roles administrativos predeterminados directamente en el EAC, pero no puede personalizar el control de acceso basado en funciones (RBAC). Para más información, vea [Administrar permisos de grupos de roles de administración en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Administración de dominios
<a name="BKMK_domainmanagement"> </a>

Los dominios administrados son dominios que están protegidos por EOP. En el EAC, se pueden ver los dominios administrados y editar los tipos de dominio. El aprovisionamiento y la administración de dominios se realizan en el Centro de administración de Office 365 y los cambios se reflejan en el EAC. Para obtener más información, vea [Administrar dominios aceptados en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Subdominios coincidentes
<a name="BKMK_EOP_Match_Subdomains"> </a>

En EOP, puede habilitar el flujo del correo para los subdominios de un dominio administrado. Para obtener más información, vea [Habilitar el flujo de correo electrónico para los subdominios en EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Bloqueo perimetral basado en directorios (DBEB)
<a name="BKMK_DBEB"> </a>

La característica Bloqueo perimetral basado en directorios permite rechazar mensajes para destinatarios no válidos en el perímetro de la red de servicio. El DBEB permite que los administradores agreguen destinatarios habilitados para correo a Office 365 y bloqueen todos los mensajes enviados a direcciones de correo electrónico que no están presentes en Office 365. Si un mensaje se envía a una dirección de correo electrónico válida que está presente en Office 365, el mensaje continúa a través de las demás capas de filtrado del servicio (antimalware, correo no deseado, reglas de transporte). Si la dirección no se encuentra, el servicio bloquea el mensaje incluso antes de que se produzca el filtrado y se envía un informe de no entrega (NDR) al remitente informándole que su mensaje no se entregó. 
  
Para habilitar DBEB es necesario realizar una configuración de usuario y de dominio. Para obtener más información, vea [Usar bloqueo perimetral basado en directorios para rechazar mensajes enviados a destinatarios no válidos](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilidad de características
<a name="BKMK_DBEB"> </a>

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  

