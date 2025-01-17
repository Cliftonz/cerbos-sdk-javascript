<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [CheckResourcesRequest](./core.checkresourcesrequest.md)

## CheckResourcesRequest interface

Input to [Client.checkResources()](./core.client.checkresources.md)<!-- -->.

**Signature:**

```typescript
export interface CheckResourcesRequest 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [auxData?](./core.checkresourcesrequest.auxdata.md) |  | [AuxData](./core.auxdata.md) | _(Optional)_ Auxiliary data. |
|  [includeMetadata?](./core.checkresourcesrequest.includemetadata.md) |  | boolean | _(Optional)_ Include [additional metadata](./core.checkresourcesresultmetadata.md) in the results? |
|  [principal](./core.checkresourcesrequest.principal.md) |  | [Principal](./core.principal.md) | The principal to check. |
|  [requestId?](./core.checkresourcesrequest.requestid.md) |  | string | _(Optional)_ An identifier for tracing the request. |
|  [resources](./core.checkresourcesrequest.resources.md) |  | [ResourceCheck](./core.resourcecheck.md)<!-- -->\[\] | The resources and actions to check. |

