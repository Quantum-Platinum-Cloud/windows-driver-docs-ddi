---
UID: NS:d3dkmthk._D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
title: _D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION (d3dkmthk.h)
description: The D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION structure describes the shared primary surface that an application just unlocked.
old-location: display\d3dkmt_sharedprimaryunlocknotification.htm
ms.date: 05/10/2018
keywords: ["D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION structure"]
ms.keywords: D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION, D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION structure [Display Devices], OpenGL_Structs_1766625b-9d47-4e86-9f24-08706541c167.xml, _D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION, d3dkmthk/D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION, display.d3dkmt_sharedprimaryunlocknotification
req.header: d3dkmthk.h
req.include-header: D3dkmthk.h
req.target-type: Windows
req.target-min-winverclnt: Available in Windows Vista and later versions of the Windows operating systems.
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
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
tech.root: display
req.typenames: D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
f1_keywords:
 - _D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
 - d3dkmthk/_D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
 - D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
 - d3dkmthk/D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dkmthk.h
api_name:
 - _D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
 - D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION
---

# _D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION structure


## -description

The D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION structure describes the shared primary surface that an application just unlocked.

## -struct-fields

### -field AdapterLuid [in]

The locally unique identifier (<a href="/windows-hardware/drivers/ddi/igpupvdev/ns-igpupvdev-_luid">LUID</a>) of the graphics adapter on which the GDI shared primary surface exists.

### -field VidPnSourceId [in]

The zero-based identification number of the video present source in a path of a video present network (VidPN) topology on which the GDI shared primary surface exists.

## -see-also

<a href="/windows-hardware/drivers/ddi/d3dkmthk/nf-d3dkmthk-d3dkmtsharedprimaryunlocknotification">D3DKMTSharedPrimaryUnLockNotification</a>

