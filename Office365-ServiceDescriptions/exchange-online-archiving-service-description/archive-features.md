---
title: Características de archivo de Archivado de Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: En las secciones siguientes se describen las características de archivo de archivado de Microsoft Exchange Online.
ms.openlocfilehash: 2bffa9fccb2c040fde4edcf8a5c80f3bc109bba2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037035"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Características de archivo de Archivado de Exchange Online

En las secciones siguientes se describen las características de archivo de archivado de Microsoft Exchange Online.
  
## <a name="archive-mailbox"></a>Buzón de archivo

Archivado de Exchange Online ofrece a los usuarios capacidades avanzadas de archivo con la característica de buzón de archivo. Un buzón de archivo es un buzón especializado que aparece junto a las carpetas del buzón principal de los usuarios en Outlook o Outlook Web App. Los usuarios pueden acceder al archivo como si accedieran a su buzón principal y realizar búsquedas en ambos buzones.
  
Los administradores pueden habilitar la característica de archivo para usuarios específicos desde el Centro de administración de Exchange (EAC) o desde Windows PowerShell remoto. Para obtener más información, vea [Habilitar o deshabilitar un buzón de archivo en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).
  
> [!IMPORTANT]
>  No se permite copiar mensajes en Archivado de Exchange Online para su archivo con el registro en diario, o mediante reglas de transporte o reenvío automático. >  El buzón de archivo de un usuario está diseñado exclusivamente para dicho usuario. Microsoft se reserva el derecho de denegar el archivado ilimitado si el buzón de archivo de un usuario se usa para almacenar datos de archivo de otros usuarios. 
  
### <a name="move-messages-to-exchange-online-archiving"></a>Mover mensajes a Exchange Online Archiving

Para facilitar el acceso en línea a sus mensajes, los usuarios pueden arrastrar mensajes desde archivos .pst y colocarlos en el archivo. También pueden mover de manera automática elementos de correo desde el buzón principal hasta el buzón de archivo con ayuda de las directivas de archivo. Así, se reduce el tamaño del buzón principal y se consigue un mejor rendimiento. Aunque Exchange Hosted Archive funciona de otra manera (crea una copia secundaria de todos los mensajes en el archivo), los requisitos de retención pueden cumplirse en ambos escenarios. Para obtener más información sobre otros métodos que permiten mover mensajes al archivo, vea [Buzones de archivo en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).
  
### <a name="import-data-to-the-archive"></a>Importar datos al archivo

Para importar datos al archivo, los usuarios pueden:
  
- Importar datos desde un archivo .pst con el Asistente para importar y exportar de Outlook.
    
- Arrastrar mensajes de correo desde archivos .pst hasta el archivo.
    
- Arrastrar mensajes de correo desde el buzón principal hasta el archivo.
    
- Permitir que las directivas de archivo muevan de manera automática los mensajes de correo desde el buzón principal, en función de la antigüedad de los mensajes. Para obtener más información, vea [Etiquetas de retención y directivas de retención](https://go.microsoft.com/fwlink/p/?LinkId=314153).
    
> [!NOTE]
> Los administradores también pueden usar el servicio de importación de Office 365 para importar archivos .pst a los buzones de archivos basados en la nube de los usuarios. Para obtener más información, vea [Usar la carga en la red para importar archivos PST en Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074). 
  
## <a name="deleted-item-recovery"></a>Recuperación de elementos eliminados

Los usuarios pueden restaurar elementos que han eliminado con anterioridad desde cualquier carpeta de correo de su archivo. Cuando se elimina un elemento, permanece en la carpeta Elementos eliminados del archivo. El elemento permanece ahí hasta que el usuario lo elimina de forma manual o hasta que las directivas de retención lo quitan de forma automática.
  
Cuando el elemento se quita de la carpeta Elementos eliminados del archivo, se conserva en la carpeta Elementos recuperables del archivo durante 14 días, antes de eliminarse de forma permanente. Los usuarios pueden recuperar estos elementos con la característica **Recuperar elementos eliminados** de Microsoft Outlook o Outlook Web App. 
  
Si un usuario purga de manera manual un elemento de la carpeta Elementos recuperables, los administradores pueden recuperarlo a lo largo de los 14 días siguientes con la característica Recuperación de un único elemento. Esta característica permite a los administradores realizar una búsqueda en varios buzones para buscar los elementos que se han purgado y, después, transferirlos desde el buzón de correo de detección hasta los buzones de los usuarios con el cmdlet  `Search-Mailbox` de Windows PowerShell. Para obtener más información, vea [Habilitar o deshabilitar la recuperación de elementos individuales de un buzón de correo](https://go.microsoft.com/fwlink/p/?LinkId=314155).
  
> [!NOTE]
>  El período predeterminado de recuperación de un único elemento es de 14 días, pero se puede personalizar en situaciones determinadas. >  Si un administrador ha establecido el buzón de un usuario en conservación local o retención por juicio, los elementos purgados se conservan de manera indefinida y no se aplica este período de 14 días. 
  
## <a name="deleted-mailbox-recovery"></a>Recuperación de buzones eliminados

Cuando los administradores eliminan usuarios de una implementación local de Exchange Server, también se eliminan los archivos correspondientes. El equipo de soporte técnico de Office 365 puede recuperar los buzones de archivo eliminados si resulta necesario. Los archivos recuperados conservarán todo el correo que contenían almacenado en el momento de su eliminación.
  
> [!IMPORTANT]
> A partir del momento en que se elimina el buzón de un usuario, los administradores tienen 30 días para solicitar la recuperación del buzón de archivo. Transcurrido este período, los buzones de archivo ya no pueden recuperarse. 
  
## <a name="mailbox-service-redundancy"></a>Redundancia de servicios de buzón

Buzones de archivo en Archiving en línea de Exchange se replican en varias copias de base de datos, en centros de datos dispersos geográficamente de Microsoft, para proporcionar capacidad de restauración de datos en caso de error de infraestructura de mensajería. Si hay errores a gran escala, se inicia la administración de continuidad empresarial. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, vea [Descripción del servicio de archivado de Exchange Online](exchange-online-archiving-service-description.md).
  
