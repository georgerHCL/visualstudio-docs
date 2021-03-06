---
title: "This related method is the backing method for the following default insert, update, or delete methods | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 62afa6da-97cf-48b9-8de3-33e4d72a0377
caps.latest.revision: 3
author: "gewarren"
ms.author: "gewarren"
manager: "ghogen"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# This related method is the backing method for the following default insert, update, or delete methods
This related method is the backing method for the following default insert, update, or delete methods. If it is deleted, these methods will be deleted as well. Do you wish to continue?  
  
 The selected `DataContext` method is currently used as one of the Insert, Update, or Delete methods for one of the entity classes on the O/R Designer. Deleting the selected method will cause the entity class that was using this method to revert to the default run-time behavior for performing the Insert, Update, or Delete during an update.  
  
### To delete the selected method, causing the entity class to use runtime updates  
  
-   Click **Yes**.  
  
     The selected method is deleted and any classes that used this method for overriding update behavior are reverted to using the default LINQ to SQL runtime behavior.  
  
### To close the message box, leaving the selected method unchanged  
  
-   Click **No**.  
  
     The message box closes and no changes are made.  
  
## See Also  
 [DataContext Methods (O/R Designer)](../data-tools/datacontext-methods-o-r-designer.md)   
 [How to: Assign stored procedures to perform updates, inserts, and deletes (O/R Designer)](../data-tools/how-to-assign-stored-procedures-to-perform-updates-inserts-and-deletes-o-r-designer.md)   
 [LINQ to SQL Tools in Visual Studio](../data-tools/linq-to-sql-tools-in-visual-studio2.md)   
 [LINQ to SQL](/dotnet/framework/data/adonet/sql/linq/index)