---
title: Descripción del servicio de archivado de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: Archivado de Microsoft Exchange Online es una Microsoft Office 365 basada en la nube, archivada solución de clase empresarial para las organizaciones que han implementado Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 y versiones posteriores), o suscribirse a ciertas Planes de Exchange Online o Office 365. Archivado de Exchange Online ayuda a estas organizaciones con sus archiving, cumplimiento de normativas, y simplificación de la infraestructura local y, desde allí, reducir los costos y facilitar las cargas de TI los desafíos de exhibición de documentos electrónicos.
ms.openlocfilehash: d88d336f0e5b30a245b6c90c7cc488ca6d5dfc54
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036968"
---
# <a name="exchange-online-archiving-service-description"></a>Descripción del servicio de archivado de Exchange Online

Archivado de Microsoft Exchange Online es una Microsoft Office 365 basada en la nube, archivada solución de clase empresarial para las organizaciones que han implementado Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 y versiones posteriores), o suscribirse a ciertas Planes de Exchange Online o Office 365. Archivado de Exchange Online ayuda a estas organizaciones con sus archiving, cumplimiento de normativas, y simplificación de la infraestructura local y, desde allí, reducir los costos y facilitar las cargas de TI los desafíos de exhibición de documentos electrónicos.
  
Como un servicio online de Microsoft Office 365, Archivado de Exchange Online fue diseñado para ayudar a satisfacer la necesidad de una seguridad sólida, confiabilidad y productividad de los usuarios. Para obtener más información acerca de Office 365, lo cual incluye funciones comunes a todos los servicios en línea de Office 365, vea [Descripción del servicio de la plataforma de Office 365](../office-365-platform-service-description/office-365-platform-service-description.md).
  
Para comprar el Archivado de Exchange Online, consulte [Archivado de Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=314176).
  
Para comparar las características de los diferentes planes, consulte [Comparar los planes de Office 365 para empresas](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
> [!TIP]
> Puede exportar, guardar e imprimir páginas en las descripciones de los servicios de Office 365. Obtenga más información sobre cómo [exportar varias páginas](https://go.microsoft.com/fwlink/?LinkId=403349). 
  
## <a name="exchange-online-archiving-plans"></a>Planes de Archivado de Exchange Online
<a name="bkmk_EOA_Plans"> </a>

Archivado de Exchange Online está disponible a través de los siguientes planes.
  
|**Plan**|**Descripción**|
|:-----|:-----|
|**Archivado de Exchange Online para Exchange Server** <br/> |Archivado basado en la nube para usuarios con buzones de correo primarios en Exchange Server 2013 o Exchange 2010 (SP2 o posterior).  <br/> Si desea agregar un archivo basado en la nube a un buzón principal que está en un servidor de Exchange local, necesita configurar una implementación híbrida. Para obtener más información sobre las implementaciones híbridas, consulte [Implementaciones híbridas de Exchange Server](https://technet.microsoft.com/library/jj200581%28v=exchg.150%29.aspx).  <br/> |
|**Archivado de Exchange Online para Exchange Server (a través de Enterprise CAL Suite)** <br/> |Archivado basado en la nube para usuarios con buzones de correo primarios en Exchange Server 2013 o en Exchange 2010 (SP2 o posterior). Para obtener más información, vea [Resumen de licencias: licencias de Core CAL Suite y de Enterprise CAL Suite](https://go.microsoft.com/fwlink/p/?LinkId=314160).  <br/> |
|**Archivado de Exchange Online para Exchange Online** <br/> | Archivo basado en nube y conservación local como complemento para los siguientes planes: <sup>1, 2</sup>,  <br/>  Plan 1 de Exchange Online  <br/>  Quiosco de Exchange Online  <br/>  Office 365 Empresa Essentials  <br/>  Office 365 Empresa Premium  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F1  <br/> > [!NOTE]>  Los planes siguientes incluyen funcionalidad de archivado y no requieren Archivado de Exchange Online como complemento: >  Office 365 Educación A1 >  Office 365 Educación A3 >  Office 365 Educación A5 >  Office 365 Enterprise E3 >  Office 365 Enterprise E5 >  Plan 2 de Exchange Online >  Para obtener detalles acerca de la capacidades de archivo de los buzones de correo de Exchange Online, consulte [Buzones de archivo de Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).           |
   
> [!NOTE]
> <sup>1</sup> No se necesita una implementación híbrida para las organizaciones basadas exclusivamente en la nube en las que no hay buzones de correo ubicados en un servidor Exchange local. Sin embargo, si existen buzones locales, la implementación híbrida es necesaria. > <sup>2</sup> Los planes de Plan 1 de Exchange Online y Office 365 Empresa tienen un [límite de tamaño de buzón de correo y archivo](https://go.microsoft.com/fwlink/?LinkId=330039). El complemento Archivado de Exchange Online para Exchange Online agrega [Retención local y retención por juicio](compliance-and-security-features.md#in-place-hold-and-litigation-hold) y funcionalidad de archivado basada en la nube sin limitaciones. 
  
¿Está buscando información sobre todos los planes de Office 365? Office 365 está disponible en una variedad de planes a fin de satisfacer las necesidades de su organización de la mejor manera. Para obtener más información sobre distintos planes, incluidas las opciones de los planes independientes e información sobre cómo cambiar de un plan a otro, consulte [Opciones de planes de Office 365](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Requisitos
<a name="bkmk_EOA_Plans"> </a>

Para utilizar Archivado de Exchange Online para Exchange Server, los buzones de correo del usuario deben estar ubicados en Exchange Server 2013 o Exchange Server 2010 (SP2 o posterior).
  
### <a name="federated-identity-and-single-sign-on"></a>Identidad federada e inicio de sesión único

Los administradores pueden utilizar el enfoque de inicio de sesión único para la autenticación de Office 365 con Active Directory local. Para lograrlo, los administradores pueden configurar los Servicios de federación de Active Directory (un servicio de Microsoft Windows Server® 2008) para federar con Microsoft Federation Gateway. Una vez configurados los Servicios de federación de Active Directory, todos los usuarios de Office 365 cuyas identidades estén basadas en el dominio federado pueden utilizar su inicio de sesión corporativo existente para autenticarse automáticamente en Office 365.
  
### <a name="user-subscriptions"></a>Suscripciones de usuario

Cada usuario que acceda al servicio de Archivado de Exchange Online debe tener una suscripción de Archivado de Exchange Online. Cada suscripción de archivado de correo electrónico solo se puede utilizar para almacenar los datos de mensajería de un usuario.
  
## <a name="unlimited-archive-storage-quota"></a>Cuota de almacenamiento de archivo ilimitada
<a name="bkmk_EOA_Plans"> </a>

 La característica de archivo ilimitado en Office 365 (denominada archivado de expansión automática) proporciona una cantidad ilimitada de almacenamiento en los buzones de archivo. Cada suscriptor de Archivado de Exchange Online recibe inicialmente 100 GB de almacenamiento en el buzón de archivo. Cuando el archivado de expansión automática está activado, se agrega almacenamiento adicional automáticamente cuando se alcanza la capacidad de almacenamiento de 100 GB. Para obtener más información, vea [Información general sobre el archivado ilimitado en Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Vea el [Mapa de ruta de Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obtener información sobre la disponibilidad. 
  
> [!IMPORTANT]
> Los administradores no pueden ajustar la cuota de almacenamiento. 
  
> [!IMPORTANT]
> No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios. 
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Disponibilidad de características en los planes de Archivado de Exchange Online
<a name="bkmk_EOA_Plans"> </a>

||||
|:-----|:-----|:-----|
|**Característica** <br/> |**Archivado de Exchange Online para Exchange Server<sup>1</sup>**          <br/> |**Archivado de Exchange Online para Exchange Online<sup>2</sup>** <br/> |
|**[Características de archivo de Archivado de Exchange Online](archive-features.md)** <br/> |||
|Buzón de archivo  <br/> |Sí  <br/> |Sí  <br/> |
|Mover mensajes con la directiva de archivado  <br/> |Sí  <br/> |Sí  <br/> |
|Importar datos al archivo  <br/> |Sí  <br/> |Sí  <br/> |
|Recuperación de elementos eliminados  <br/> |Sí  <br/> |Sí  <br/> |
|Recuperación de buzones eliminados  <br/> |Sí  <br/> |Sí  <br/> |
|Copia de seguridad del buzón  <br/> |Sí  <br/> |Sí  <br/> |
|**[Características de cliente de Exchange Online Archiving](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Sí  <br/> |Sí  <br/> |
|Outlook Web App  <br/> |Sí  <br/> |Sí  <br/> |
|**[Características de cumplimiento y seguridad en Archivado de Exchange Online](compliance-and-security-features.md)** <br/> |||
|Directivas de retención  <br/> |Sí  <br/> |Sí  <br/> |
|Conservación local y retención por juicio<sup>6</sup> <br/> |Sí  <br/> |Sí  <br/> |
|Exhibición de documentos electrónicos en contexto  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado entre servidores locales y el Archivado de Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado entre clientes y el Archivado de Exchange Online  <br/> |Sí  <br/> |Sí  <br/> |
|Cifrado: S/MIME y PGP  <br/> |Sí  <br/> |Sí  <br/> |
|IRM con Azure Information Protection  <br/> |No  <br/> |No hay<sup>4</sup> <br/> |
|IRM con Windows Server AD RMS  <br/> |Sí<sup>5</sup> <br/> |Sí<sup>5</sup> <br/> |
|Auditoría  <br/> |Sí  <br/> |Sí  <br/> |
   

> <sup>1</sup> Los buzones de correo del usuario deben residir en Exchange 2010 SP2 u otra versión posterior.
 <br/><sup>2</sup> un archivo local sólo se puede usar para archivar el correo para un único usuario o entidad para la que se ha aplicado una licencia. Está prohibido el uso de un archivo local como un medio para almacenar el correo de varios usuarios o entidades. Por ejemplo, los administradores de TI no se pueden crear buzones de correo compartidos y tienen los usuarios copiar (a través del campo Cc o CCO, o a través de una regla de transporte) de un buzón compartido con el fin explícito de archivado. <br/> <sup>3</sup> para obtener una lista de las versiones compatibles de Microsoft Outlook, vea [Características de cliente en Exchange Online Archiving](client-features.md). 
 <br/><sup>4</sup> protección de la información de azure no se incluye, pero puede adquirirse como un complemento independiente y habilitará las características de Information Rights Management (IRM) compatibles. Algunas características de protección de la información de Azure requieren una suscripción a Office 365 ProPlus, que no se incluye con Office 365 para el negocio, Business Premium de Office 365, Office 365 Enterprise E1, Office 365 educación o F1 Enterprise de Office 365. <br/><sup>5</sup> Windows Server AD RMS es un servidor local que debe comprarse y administrarse por separado para habilitar las características de IRM admitidas. 
 <br/><sup>6</sup> Si coloca un buzón en Conservación local o retención por juicio, la conservación o retención se aplica al buzón principal y al buzón de archivo. 