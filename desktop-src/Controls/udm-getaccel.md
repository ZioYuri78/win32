---
title: UDM\_GETACCEL message
description: Retrieves acceleration information for an up-down control.
ms.assetid: 794538d6-ca01-4f05-82d1-ce7bc0f76f64
keywords:
- UDM_GETACCEL message Windows Controls
topic_type:
- apiref
api_name:
- UDM_GETACCEL
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.date: 05/31/2018
ms.topic: article
ms.author: windowssdkdev
ms.prod: windows
ms.technology: desktop
---

# UDM\_GETACCEL message

Retrieves acceleration information for an up-down control.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

Number of elements in the array specified by *lParam*.

</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to an array of [**UDACCEL**](/windows/win32/Commctrl/ns-commctrl-_udaccel?branch=master) structures that receive acceleration information.

</dd> </dl>

## Return value

The return value is the number of accelerators currently set for the control.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



## See also

<dl> <dt>

[**UDM\_SETACCEL**](udm-setaccel.md)
</dt> </dl>

 

 




