---
title: Dominios
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Cuando se agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico de Office 365 y otros servicios de su nombre empresarial. Cuando se complete el asistente, su dirección de correo empresarial empieza a Office 365 en lugar de a su proveedor de correo electrónico actual. Para obtener más información, vea Agregar los usuarios y dominios a Office 365. Si usa Office 365 operado por 21Vianet, vea Verify su dominio.
ms.openlocfilehash: 47c378482b8a8d09e2f2516968af99af9472c641
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036967"
---
# <a name="domains"></a>Dominios

Cuando se agrega un dominio, un asistente paso a paso le ayuda a agregar usuarios y convertir las direcciones de correo electrónico de Office 365 y otros servicios de su nombre empresarial. Cuando se complete el asistente, su dirección de correo empresarial empieza a Office 365 en lugar de a su proveedor de correo electrónico actual. Para obtener más información, vea [Agregar los usuarios y dominios a Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Si usa Office 365 operado por 21Vianet, vea [Verify su dominio](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409).
  
## <a name="custom-domains"></a>Dominios personalizados
<a name="BKMK_CustomDomains"> </a>

Puede agregar hasta 900 dominios a su suscripción de Office 365. Sin embargo, no se puede agregar un dominio a Office 365 que ya está usando en otro servicio de nube de Microsoft. Esto significa que no se puede agregar el mismo dominio para varias suscripciones de Office 365. Para obtener más información, consulte [Preguntas más frecuentes de dominios](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Dominios de segundo y tercer nivel
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Con Office 365 Enterprise y Office 365 Empresa, puede agregar un dominio de cualquier nivel, incluidos los dominios de tercer nivel, como marketing.contoso.com. Vea [Agregar subdominios personalizados o varios dominios a Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409). Si usa Office 365 operado por 21Vianet, consulte [Agregar subdominios personalizados o varios dominios a Office 365 operado por 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409).
  
## <a name="domain-verification-and-managing-dns-records"></a>Comprobación de dominios y administración de registros DNS
<a name="BKMK_ManagingDNSRecords"> </a>

Con Office 365, puede administrar todos los registros DNS en su proveedor de host DNS, o bien optar por que Office 365 se encargue de configurar y administrar automáticamente los registros DNS de su dominio. Si continúa administrando los registros, deberá cambiar registros específicos para que apunten a servicios de Office 365 según sea necesario. Si quiere obtener una lista de registradores de dominios cuyas indicaciones paso a paso para agregar los registros, incluidos los valores específicos que deben usarse en cada registro, ofrecemos, vea [Crear registros DNS en cualquier proveedor de hospedaje DNS para Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270173) o, si usa Office 365 operado por 21Vianet, vea Create DNS records at any provider for Office 365 operated by 21Vianet (Crear registros DNS en cualquier proveedor de Office 365 operado por 21Vianet). 
  
Si Office 365 administra los registros DNS de su dominio, primero debe cambiar los registros de servidor de nombres de su dominio para que apunten a Office 365. A continuación, Office 365 configura sus servicios de Office 365 y, luego, los registros DNS de su dominio se administran en Office 365.
  
Si su dominio está registrado en GoDaddy, Office 365 puede crear los registros necesarios en GoDaddy. 
  
Sin importar dónde estén albergados sus registros DNS, puede configurar los registros DNS para utilizar un sitio web público albergado en Office 365 o con un proveedor de host diferente. 
  
Office 365comprueba de forma proactiva los registros DNS para buscar y solucionar problemas relacionados con el DNS. Si los registros de DNS no coinciden con los resultados esperados, recibirá una notificación en el Centro de administración de Office 365 con información que le indica cómo solucionar los posibles problemas identificados.
  
Para obtener más información, vea [Cómo administra Office 365 los registros DNS](https://go.microsoft.com/fwlink/p/?LinkID=270144) o, para Office 365 operado por 21Vianet, vea [Create DNS records for Office 365 when you manage your DNS records ](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409).
  
## <a name="sharing-a-domain"></a>Compartir un dominio
<a name="BKMK_ManagingDNSRecords"> </a>

Puede probar Office 365 con algunos direcciones de correo electrónico para un dominio en Office 365 y algunas en su proveedor de correo electrónico anterior. Esto se recomienda sólo para su uso durante una prueba piloto de Office 365, ya que requiere pasos de configuración adicionales y tiene algunas limitaciones para servicios de Office 365. Para obtener más información, vea:
  
- [Pilotar Office 365 para una empresa pequeña](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilotar Office 365 para una gran empresa (mediante FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Disponibilidad de características
<a name="BKMK_ManagingDNSRecords"> </a>

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio de la plataforma de Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

