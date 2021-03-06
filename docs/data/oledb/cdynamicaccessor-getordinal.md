---
title: "CDynamicAccessor::GetOrdinal | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["CDynamicAccessor.GetOrdinal", "ATL::CDynamicAccessor::GetOrdinal", "CDynamicAccessor::GetOrdinal", "ATL.CDynamicAccessor.GetOrdinal", "GetOrdinal"]
dev_langs: ["C++"]
helpviewer_keywords: ["GetOrdinal method"]
ms.assetid: 2095b71c-a7a4-4034-89a1-77a78cb9633f
caps.latest.revision: 8
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "data-storage"]
---
# CDynamicAccessor::GetOrdinal
Retrieves the column number given a column name.  
  
## Syntax  
  
```  
  
      bool GetOrdinal(  
   const CHAR* pColumnName,  
   DBORDINAL* pOrdinal   
) const throw( );  
bool GetOrdinal(  
   const WCHAR* pColumnName,  
   DBORDINAL* pOrdinal   
) const throw( );  
```  
  
#### Parameters  
 `pColumnName`  
 [in] A pointer to a character string containing the column name.  
  
 *pOrdinal*  
 [out] A pointer to the column number.  
  
## Return Value  
 Returns **true** if a column with the specified name is found. Otherwise, this function returns **false**.  
  
## Requirements  
 **Header:** atldbcli.h  
  
## See Also  
 [CDynamicAccessor Class](../../data/oledb/cdynamicaccessor-class.md)