---
title: "Compiler Error C3333 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C3333"]
dev_langs: ["C++"]
helpviewer_keywords: ["C3333"]
ms.assetid: 51693978-fba6-435a-a696-74735cc875de
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# Compiler Error C3333
'type library': cannot #import corrupt type library  
  
 The type library specified in the `#import` statement is unreadable by the compiler. You may want to either regenerate the type library, if possible, or request a new type library from your supplier. You may want to use the OLE Viewer, supplied with Visual C++, to view the type library file to see what is the matter with it.