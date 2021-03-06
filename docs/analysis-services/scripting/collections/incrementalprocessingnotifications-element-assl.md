---
title: "IncrementalProcessingNotifications Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.service: ""
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "IncrementalProcessingNotifications Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
helpviewer_keywords: 
  - "IncrementalProcessingNotifications element"
ms.assetid: 46f3c9d0-46cc-4833-8f15-7831207f57ce
caps.latest.revision: 17
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# IncrementalProcessingNotifications Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Contains the collection of [IncrementalProcessingNotification](../../../analysis-services/scripting/objects/incrementalprocessingnotification-element-assl.md) elements that provide information to the [ProactiveCaching](../../../analysis-services/scripting/objects/proactivecaching-element-assl.md) element about queries to execute to determine the progress of incremental processing.  
  
## Syntax  
  
```xml  
  
<ProactiveCachingIncrementalProcessingBinding>  
   <IncrementalProcessingNotifications>  
      <IncrementalProcessingNotification>...  
   ...</IncrementalProcessingNotification>  
   </IncrementalProcessingNotifications>  
</ProactiveCachingQueryBinding>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|1-1: Required element that occurs once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[ProactiveCachingIncrementalProcessingBinding](../../../analysis-services/scripting/data-type/proactivecachingincrementalprocessingbinding-data-type-assl.md)|  
|Child elements|[IncrementalProcessingNotification](../../../analysis-services/scripting/objects/incrementalprocessingnotification-element-assl.md)|  
  
## Remarks  
 The corresponding element in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.IncrementalProcessingNotificationCollection>.  
  
## See Also  
 [Collections &#40;ASSL&#41;](../../../analysis-services/scripting/collections/collections-assl.md)  
  
  
