---
title: "ICorDebugValueBreakpoint Interface1 | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugValueBreakpoint"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugValueBreakpoint"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugValueBreakpoint interface [.NET Framework debugging]"
ms.assetid: c02338fe-da6c-467f-9567-70ebb387e901
caps.latest.revision: 11
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugValueBreakpoint Interface1
Extends the ICorDebugBreakpoint interface to provide access to specific values.  
  
## Methods  
  
|Method|Description|  
|------------|-----------------|  
|[GetValue Method](../../../../docs/framework/unmanaged-api/debugging/icordebugvaluebreakpoint-getvalue-method.md)|Gets an interface pointer to an ICorDebugValue object that represents the value of the object upon which the breakpoint is set.|  
  
## Remarks  
  
> [!NOTE]
>  This interface does not support being called remotely, either cross-machine or cross-process.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [Debugging Interfaces](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)