---
UID: NF:portcls.IPortClsNotifications.SendNotification
title: IPortClsNotifications::SendNotification (portcls.h)
description: Sends a notification to the listening UWP apps, to allow for communications between audio modules and UWP apps.
old-location: audio\iportclsnotifications_sendnotification.htm
tech.root: audio
ms.date: 05/08/2018
keywords: ["IPortClsNotifications::SendNotification"]
ms.keywords: IPortClsNotifications interface [Audio Devices],SendNotification method, IPortClsNotifications.SendNotification, IPortClsNotifications::SendNotification, SendNotification, SendNotification method [Audio Devices], SendNotification method [Audio Devices],IPortClsNotifications interface, audio.iportclsnotifications_sendnotification, portcls/IPortClsNotifications::SendNotification
req.header: portcls.h
req.include-header: Portcls.h
req.target-type: Universal
req.target-min-winverclnt: Available in Windows 10, version 1703 and later versions of Windows.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Portcls.lib
req.dll: 
req.irql: PASSIVE_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - IPortClsNotifications::SendNotification
 - portcls/IPortClsNotifications::SendNotification
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Portcls.lib
 - Portcls.dll
api_name:
 - IPortClsNotifications::SendNotification
---

# IPortClsNotifications::SendNotification


## -description

Sends a notification to the listening UWP apps, to allow for communications between audio modules and UWP apps.

## -parameters

### -param NotificationId [in]


KSNOTIFICATIONID_AudioModule

### -param NotificationBuffer

### -param PPCNOTIFICATION* [in]

Pointer to a <a href="/windows-hardware/drivers/ddi/portcls/ns-portcls-_pcnotification_buffer">PCNOTIFICATION_BUFFER</a> structure to send to the listening audio module UWP clients.

## -remarks

Pointer to the PCNOTIFICATION structure to send to Audio Module clients.

The expected format of the payload is a <a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ksaudiomodule_notification">KSAUDIOMODULE_NOTIFICATION</a> structure. The miniport driver can optionally send additional information immediately following the <b>KSAUDIOMODULE_NOTIFICATION</b> structure that will be untouched and sent to the Audio Module clients.



For more information about audio modules, see <a href="/windows-hardware/drivers/audio/implementing-audio-module-communication">Implementing Audio Module Discovery</a>.

## -see-also

<a href="/windows-hardware/drivers/ddi/portcls/nn-portcls-iportclsnotifications">IPortClsNotifications</a>

