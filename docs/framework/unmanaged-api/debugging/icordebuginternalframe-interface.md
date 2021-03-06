---
title: "ICorDebugInternalFrame Interface1 | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugInternalFrame"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugInternalFrame"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugInternalFrame interface [.NET Framework debugging]"
ms.assetid: bb4772ca-0d54-4185-b738-7a6ffe9ea85a
caps.latest.revision: 15
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugInternalFrame Interface1
Represents a runtime-internal frame on the stack. This interface is a subclass of the ICorDebugFrame interface.  
  
## Methods  
  
|Method|Description|  
|------------|-----------------|  
|[GetFrameType Method](../../../../docs/framework/unmanaged-api/debugging/icordebuginternalframe-getframetype-method.md)|Gets the type of this internal frame.|  
  
## Remarks  
  
> [!NOTE]
>  This interface does not support being called remotely, either cross-machine or cross-process.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See Also  
 [Debugging Interfaces](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)