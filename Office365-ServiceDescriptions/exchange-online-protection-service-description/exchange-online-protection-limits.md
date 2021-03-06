---
title: Límites de Exchange Online Protection
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Los siguientes límites existen actualmente para Exchange Online Protection. Estos límites no son configurables, a menos que se especifique lo contrario.
ms.openlocfilehash: 2e2efe4693cb7e5cdf52b4d035512657c39f03c2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037100"
---
# <a name="exchange-online-protection-limits"></a>Límites de Exchange Online Protection

Los siguientes límites existen actualmente para Exchange Online Protection. Estos límites no son configurables, a menos que se especifique lo contrario. 
  
> [!TIP]
> Para obtener más información acerca de los límites en Exchange Online, vea [Límites de Exchange Online](../exchange-online-service-description/exchange-online-limits.md). Los límites de la regla de transporte se aplican también a los clientes de EOP independiente. Los límites de tasa de destinatarios y tasa de mensajes de Exchange Online no se aplican a los clientes de EOP independiente. 
  
- **Límite de dominio** Puede agregar hasta 900 dominios por espacio empresarial. Los subdominios pueden incluirse en este límite de 900, o bien, si es necesario, como parte de una opción global de subdominios coincidentes. Para obtener más información, vea [Administrar dominios aceptados en EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Límite de tamaño de mensajes** El tamaño máximo de un mensaje para clientes de EOP independiente, con archivos adjuntos, es de 150 MB. 
    
- **Número de mensajes salientes enviados** El límite de cantidad de mensajes salientes que se envían a través de EOP es lo suficientemente elevado como para garantizar la comunicación normal por correo electrónico no sea tratada como correo no deseado. Si desea enviar mensajes de correo electrónico comerciales en grandes cantidades, en lugar de enviar mensajes salientes a través de EOP, le recomendamos que utilice un proveedor de servicios de correo electrónico de terceros o que los envíe a través de sus servidores de correo electrónico locales. 
    
- **Límite de destinatarios** Siempre que el host de envío pueda dividir el mensaje en "fragmentos" de menos de 500 destinatarios, no se define un límite explícito. Sin embargo, cada "fragmento" se trata realmente como un mensaje nuevo. Demasiados mensajes en un breve período, mensajes desde un host con mala reputación o mensajes con contenido dudoso podrían bloquearse o limitarse. 
    
- **Límite de listas de direcciones IP permitidas o bloqueadas** Cuando configure una lista de direcciones IP permitidas o una lista de direcciones IP bloqueadas en el filtro de conexión, puede especificar un máximo de 1.273 entradas, donde una entrada es una dirección IP única o una rango CIDR de direcciones IP de /24 a /32. 
    
- **Límite de aplazamiento de mensajes** Los mensajes aplazados permanecen en las colas durante 2 días. Los reintentos de envío de mensajes se basan en el tipo de error que se recibe del sistema de correo del destinatario. Los mensajes se vuelven a intentar cada 15 minutos. 
    
- **Período de retención en cuarentena de correo no deseado** De manera predeterminada, los mensajes de correo no deseado se envían a la cuarentena y se conservan durante 15 días. Los administradores pueden reducir este valor por medio de las directivas de filtro de contenido. 
    
- **Notificaciones de cuarentena de correo no deseado de usuario final** De manera predeterminada, si se habilitan, las notificaciones de cuarentena de correo no deseado de usuario final se envían cada 3 días. Se pueden configurar para que se envíen cada 1 a 15 días. 
    
- **Límites de seguimiento de informes y mensajes** Para conocer los límites de seguimiento de informes y mensajes, vea la sección "Informes, disponibilidad y latencia de los datos de seguimiento de mensajes" en [Informes y seguimiento de mensajes en Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Límites entre las opciones de EOP

|**Característica**|****EOP independiente****|****Características de EOP en Exchange Online****|****Exchange Enterprise CAL con servicios****|
|:-----|:-----|:-----|:-----|
|Límite de dominio  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Límite de tamaño de mensaje (incluidos datos adjuntos)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Límite de destinatarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |500 destinatarios al enviar desde un buzón de correo hospedado; consulte "Límite de destinatarios" en la sección anterior para ver otros escenarios  <br/> |Consulte "Límite de destinatarios" en la sección anterior  <br/> |
|Límite de remitentes seguros  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de remitentes bloqueados  <br/> |1024 entradas  <br/> |1024 entradas  <br/> ||
|Límite de listas de direcciones IP permitidas o bloqueadas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |1.273 entradas  <br/> |
|Límite de aplazamiento de mensajes  <br/> |2 días, se vuelve a intentar cada 15 minutos  <br/> |2 días, se vuelve a intentar cada 15 minutos  <br/> |2 días, se vuelve a intentar cada 15 minutos  <br/> |
|Período de retención en cuarentena de correo no deseado  <br/> |15 días de manera predeterminada, pero se puede reducir  <br/> |15 días de manera predeterminada, pero se puede reducir  <br/> |15 días de manera predeterminada, pero se puede reducir  <br/> |
|Notificaciones de cuarentena de correo no deseado de usuario final  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |3 días de manera predeterminada, configurable de 1 a 15 días  <br/> |
   

