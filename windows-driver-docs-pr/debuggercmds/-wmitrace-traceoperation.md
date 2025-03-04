---
title: "!wmitrace.traceoperation"
description: "The !wmitrace.traceoperation extension displays the progress messages from the tracing components in Windows."
keywords: ["!wmitrace.traceoperation Windows Debugging"]
ms.date: 05/23/2017
topic_type:
- apiref
ms.topic: reference
api_name:
- wmitrace.traceoperation
api_type:
- NA
---

# !wmitrace.traceoperation

The **!wmitrace.traceoperation** extension displays the progress messages from the tracing components in Windows.

```dbgcmd
!wmitrace.traceoperation {0 | 1 | 2} 
```

## Parameters

<span id="_______0______"></span> **0**   
Disables the display of tracing progress messages.

<span id="_______1______"></span> **1**   
Enables the display of tracing progress messages. All messages generated by the WMI tracing debugger extensions are displayed.

<span id="_______2______"></span> **2**   
Enables the display of tracing progress messages. All messages generated by the WMI tracing debugger extensions or by Tracefmt are displayed.

## DLL

Wmitrace.dll

## Additional Information

For a conceptual overview of event tracing, see the Microsoft Windows SDK.

## Remarks

This extension causes the tracing components to display verbose output. This feature is useful to troubleshoot software tracing.
