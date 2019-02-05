---
title: "hourlySchedule resource type"
description: "Hourly run schedule of a recurring device management script."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# hourlySchedule resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Hourly run schedule of a recurring device management script.


Inherits from [runSchedule](../resources/intune-devices-runschedule.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|interval|Int32|Interval in number of hours|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.hourlySchedule"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.hourlySchedule",
  "interval": 1024
}
```



