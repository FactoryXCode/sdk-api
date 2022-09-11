---
UID: NF:mfcaptureengine.IMFCaptureSource.GetStreamIndexFromFriendlyName
title: IMFCaptureSource::GetStreamIndexFromFriendlyName (mfcaptureengine.h)
description: Gets the actual device stream index translated from a friendly stream name.
helpviewer_keywords: ["GetStreamIndexFromFriendlyName","GetStreamIndexFromFriendlyName method [Media Foundation]","GetStreamIndexFromFriendlyName method [Media Foundation]","IMFCaptureSource interface","IMFCaptureSource interface [Media Foundation]","GetStreamIndexFromFriendlyName method","IMFCaptureSource.GetStreamIndexFromFriendlyName","IMFCaptureSource::GetStreamIndexFromFriendlyName","mf.imfcapturesource_getstreamindexfromfriendlyname","mfcaptureengine/IMFCaptureSource::GetStreamIndexFromFriendlyName"]
old-location: mf\imfcapturesource_getstreamindexfromfriendlyname.htm
tech.root: mf
ms.assetid: 38bc2ca8-29ff-4a23-9b78-693aaab6767f
ms.date: 12/05/2018
ms.keywords: GetStreamIndexFromFriendlyName, GetStreamIndexFromFriendlyName method [Media Foundation], GetStreamIndexFromFriendlyName method [Media Foundation],IMFCaptureSource interface, IMFCaptureSource interface [Media Foundation],GetStreamIndexFromFriendlyName method, IMFCaptureSource.GetStreamIndexFromFriendlyName, IMFCaptureSource::GetStreamIndexFromFriendlyName, mf.imfcapturesource_getstreamindexfromfriendlyname, mfcaptureengine/IMFCaptureSource::GetStreamIndexFromFriendlyName
req.header: mfcaptureengine.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 [desktop apps only]
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
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IMFCaptureSource::GetStreamIndexFromFriendlyName
 - mfcaptureengine/IMFCaptureSource::GetStreamIndexFromFriendlyName
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Mfcaptureengine.h
api_name:
 - IMFCaptureSource.GetStreamIndexFromFriendlyName
---

# IMFCaptureSource::GetStreamIndexFromFriendlyName


## -description

Gets the actual device stream index translated from a friendly stream name.

## -parameters

### -param uifriendlyName [in]

The friendly name.  Can be one of the following:

<ul>
== Not published in the SDK! =======================
<li>MF_CAPTURE_ENGINE_FIRST_SOURCE_AUDIO_STREAM</li> 
<li>MF_CAPTURE_ENGINE_FIRST_SOURCE_VIDEO_STREAM</li>
<li>MF_CAPTURE_ENGINE_FIRST_SOURCE_PHOTO_STREAM</li>
====================================================
 
<li>MF_CAPTURE_ENGINE_PREFERRED_SOURCE_STREAM_FOR_VIDEO_RECORD</li>
<li>MF_CAPTURE_ENGINE_PREFERRED_SOURCE_STREAM_FOR_VIDEO_PREVIEW</li>
<li>MF_CAPTURE_ENGINE_PREFERRED_SOURCE_STREAM_FOR_PHOTO</li>
<li>MF_CAPTURE_ENGINE_PREFERRED_SOURCE_STREAM_FOR_AUDIO</li> 
<li>MF_CAPTURE_ENGINE_PREFERRED_SOURCE_STREAM_FOR_METADATA</li>
<li>MF_CAPTURE_ENGINE_MEDIASOURCE</li> 
</ul>

### -param pdwActualStreamIndex [out]

Receives the value of the stream index that corresponds to the friendly name.

## -returns

If this method succeeds, it returns <b>S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/mfcaptureengine/nn-mfcaptureengine-imfcapturesource">IMFCaptureSource</a>
