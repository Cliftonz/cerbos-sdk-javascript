<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [PlanResourcesUnconditionalResponse](./core.planresourcesunconditionalresponse.md)

## PlanResourcesUnconditionalResponse interface

A query plan for when the specified action is always allowed or denied for the principal on resources matching the input.

**Signature:**

```typescript
export interface PlanResourcesUnconditionalResponse extends PlanResourcesResponseBase 
```
**Extends:** [PlanResourcesResponseBase](./core.planresourcesresponsebase.md)

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [kind](./core.planresourcesunconditionalresponse.kind.md) |  | [PlanKind.ALWAYS\_ALLOWED](./core.plankind.md) \| [PlanKind.ALWAYS\_DENIED](./core.plankind.md) | The type of plan. |

