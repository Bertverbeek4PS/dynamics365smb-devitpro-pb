---
title: "DrillDown Property"
ms.author: solsen
ms.custom: na
ms.date: 11/24/2020
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# DrillDown Property
> **Version**: _Available from runtime version 1.0._

Sets a drill-down for a field on a page.

## Applies to
-   Page Field


[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Property Value

**True** if a drill-down for the field is provided; otherwise, **false**. The default value is **false**.  

## Syntax

```AL
DrillDrown = true;
```
  
## Remarks  

Drill-downs are a system-wide feature of [FlowFields](../devenv-flowfields.md) that let you see the underlying transactions that make up the information shown in the FlowField. For example, if the FlowField shows an account balance, then providing a drill-down for this text box lets the user quickly see the various transactions that make up the balance shown in the field.  
  
## See Also  

[Pages Overview](../devenv-pages-overview.md)   
[Page Properties](devenv-page-properties.md)   