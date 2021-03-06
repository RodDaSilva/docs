---
title: "ICorDebugManagedCallback::ExitThread Method | Microsoft Docs"
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
  - "ICorDebugManagedCallback.ExitThread"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugManagedCallback::ExitThread"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ExitThread method [.NET Framework debugging]"
  - "ICorDebugManagedCallback::ExitThread method [.NET Framework debugging]"
ms.assetid: 62db708b-6cf0-45c5-b897-4b5c75bd2505
caps.latest.revision: 13
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugManagedCallback::ExitThread Method
Notifies the debugger that a thread that was executing managed code has exited.  
  
## Syntax  
  
```  
HRESULT ExitThread (  
    [in] ICorDebugAppDomain *pAppDomain,  
    [in] ICorDebugThread    *thread  
);  
```  
  
#### Parameters  
 `pAppDomain`  
 [in] A pointer to an ICorDebugAppDomain object that represents the application domain containing the managed thread.  
  
 `thread`  
 [in] A pointer to an ICorDebugThread object that represents the managed thread.  
  
## Remarks  
 Once the `ExitThread` callback is fired, the thread will no longer appear in thread enumerations.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [ICorDebugManagedCallback Interface](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-interface.md)