---
title: "* (Multiply) (MDX) | Microsoft Docs"
ms.custom: ""
ms.date: "03/02/2016"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.service: ""
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  
ms.tgt_pltfrm: ""
ms.topic: "language-reference"
f1_keywords: 
  - "*"
dev_langs: 
  - "kbMDX"
helpviewer_keywords: 
  - "* (multiply operator)"
  - "multiply operator (*)"
ms.assetid: 073fd098-65bd-4a30-81dd-d233d007490d
caps.latest.revision: 29
author: "Minewiskan"
ms.author: "owend"
manager: "erikre"
---
# * (Multiply) (MDX)
[!INCLUDE[ssas-appliesto-sqlas](../includes/ssas-appliesto-sqlas.md)]

  Performs an arithmetic operation that multiplies two numbers.  
  
## Syntax  
  
```  
  
Numeric_Expression * Numeric_Expression  
```  
  
#### Parameters  
 *Numeric_Expression*  
 A valid Multidimensional Expressions (MDX) expression that returns a numeric value.  
  
## Return Value  
 A value with the data type of the parameter that has the higher precedence.  
  
## Remarks  
 Both expressions must be of the same data type, or one expression must be able to be implicitly converted to the data type of the other expression. If one expression evaluates to a null value, the operator returns a null value.  
  
## See Also  
 [MDX Operator Reference &#40;MDX&#41;](../mdx/mdx-operator-reference-mdx.md)  
  
  
