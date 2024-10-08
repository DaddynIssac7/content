---
title: "WorkerNavigator: appCodeName property"
short-title: appCodeName
slug: Web/API/WorkerNavigator/appCodeName
page-type: web-api-instance-property
status:
  - deprecated
browser-compat: api.WorkerNavigator.appCodeName
---

{{APIRef("HTML DOM")}} {{Deprecated_Header}}{{AvailableInWorkers("worker")}}

The value of the **`WorkerNavigator.appCodeName`** property is
always "`Mozilla`", in any browser. This property is kept only for
compatibility purposes.

> [!NOTE]
> Do not rely on this property to return a real
> product name. All browsers return "`Mozilla`" as the value of this property.

## Value

The string "`Mozilla`".

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("WorkerNavigator.appName")}}
- {{domxref("WorkerNavigator.product")}}
