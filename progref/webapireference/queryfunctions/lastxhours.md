---
title: "LastXHours Query Function | MicrosoftDocs"
ms.date: 07/10/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 7da5fff9-c616-459d-9d1c-18563c6ea9db
author: "jimdaly"
ms.author: "jdaly"
manager: "jdaly"
---
# LastXHours Function
[!INCLUDE[./descriptions/lastxhours.md](./descriptions/lastxhours.md)]  
  
|Name|Type|Nullable|Unicode|Description|  
|----------|----------|--------------|-------------|-----------------|  
|PropertyName|Edm.String|false|false|The name of the property to evaluate. |
|PropertyValue|Edm.Int64|false|true|The value to compare. | 


## Syntax example
`?$filter=Microsoft.Dynamics.CRM.LastXHours(PropertyName=@p1,PropertyValue=@p2)&@p1='name'&@p2=42`
 
[!INCLUDE[./remarks/lastxhours.md](./remarks/lastxhours.md)]

### See also  
 [Use the Microsoft Dynamics CRM Web API](https://msdn.microsoft.com/library/mt593051.aspx)<br />
 [Web API EntityType Reference](../entitytypereference.md)<br />
 [Web API Action Reference](../actionreference.md)<br />
 [Web API Function Reference](../functionreference.md)<br />
 [Web API Query Function Reference](../queryfunctionreference.md)<br />
 [Web API EnumType Reference](../enumtypereference.md)<br />
 [Web API ComplexType Reference](../complextypereference.md)<br />
 [Web API Metadata EntityType Reference](../entitytypereference.md)<br />
 [Web API Solutions Reference](../solutionreference.md)<br />