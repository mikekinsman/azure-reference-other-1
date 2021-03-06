---
title: "Set Rowset Expressions (U-SQL) | Microsoft Docs"
ms.custom: ""
ms.date: "10/16/2017"
ms.reviewer: ""
ms.service: "data-lake-analytics"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
ms.assetid: 008e74a0-3dab-44cc-9d44-f7ec788a61e7
caps.latest.revision: 17
author: "MikeRys"
ms.author: "mrys"
manager: "ryanw"
---
# Set Rowset Expressions (U-SQL)
Set expressions allow to intersect two rowsets, to union them or to subtract one from the other. A set expression can be a top-level [U-SQL Query expression](query-statements-and-expressions-u-sql.md).  
  
<table><th align="left">Syntax</th><tr><td><pre>
Set_Rowset_Expression :=                                                                                 
     <a href="except-expression-u-sql.md">Except_Expression</a>
|    <a href="intersect-expression-u-sql.md">Intersect_Expression</a>
|    <a href="union-and-outer-union-expression-u-sql.md">Union_Expression</a>.
</pre></td></tr></table>

### See Also  
* [Query Statements and Expressions (U-SQL)](query-statements-and-expressions-u-sql.md)
* [EXCEPT Expression (U-SQL)](except-expression-u-sql.md)
* [INTERSECT Expression (U-SQL)](intersect-expression-u-sql.md)
* [UNION and OUTER UNION Expression (U-SQL)](union-and-outer-union-expression-u-sql.md)

