---
title: "HString::Detach Method | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["corewrappers/Microsoft::WRL::Wrappers::HString::Detach"]
dev_langs: ["C++"]
ms.assetid: 5006ee13-549d-40a8-8dfe-d3fb3b5e18b8
caps.latest.revision: 2
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "uwp"]
---
# HString::Detach Method
Disassociates the specified HString object from its underlying value.  
  
## Syntax  
  
```  
HSTRING Detach() throw()  
```  
  
## Return Value  
 The underlying HString value before the detach operation started.  
  
## Requirements  
 **Header:** corewrappers.h  
  
 **Namespace:** Microsoft::WRL::Wrappers  
  
## See Also  
 [HString Class](../windows/hstring-class.md)