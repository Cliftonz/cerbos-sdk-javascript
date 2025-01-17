<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [CheckResourcesResponse](./core.checkresourcesresponse.md)

## CheckResourcesResponse class

The outcome of checking a principal's permissions on a set of resources.

**Signature:**

```typescript
export declare class CheckResourcesResponse 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)({ requestId, results, })](./core.checkresourcesresponse._constructor_.md) |  | Constructs a new instance of the <code>CheckResourcesResponse</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [requestId](./core.checkresourcesresponse.requestid.md) |  | string | The identifier for tracing the request. |
|  [results](./core.checkresourcesresponse.results.md) |  | [CheckResourcesResult](./core.checkresourcesresult.md)<!-- -->\[\] | The outcomes of the permission checks for each resource. |
|  [validationErrors](./core.checkresourcesresponse.validationerrors.md) | <code>readonly</code> | [ValidationError](./core.validationerror.md)<!-- -->\[\] | Unique schema validation errors for the principal or resource attributes. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [allAllowed(resource)](./core.checkresourcesresponse.allallowed.md) |  | Check if the policy decision was that all input actions should be allowed for a resource. |
|  [allowedActions(resource)](./core.checkresourcesresponse.allowedactions.md) |  | List the actions that should be allowed for a resource. |
|  [findResult(resource)](./core.checkresourcesresponse.findresult.md) |  | Find an item from [results](./core.checkresourcesresponse.results.md) by resource. |
|  [isAllowed(check)](./core.checkresourcesresponse.isallowed.md) |  | Check if the policy decision was that an action should be allowed for a resource. |

