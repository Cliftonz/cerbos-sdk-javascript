<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [CheckResourcesResponse](./core.checkresourcesresponse.md) &gt; [allowedActions](./core.checkresourcesresponse.allowedactions.md)

## CheckResourcesResponse.allowedActions() method

List the actions that should be allowed for a resource.

**Signature:**

```typescript
allowedActions(resource: ResourceSearch): string[] | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  resource | [ResourceSearch](./core.resourcesearch.md) | the resource search criteria. |

**Returns:**

string\[\] \| undefined

`undefined` if the resource is not present in the results.

