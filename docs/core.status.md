<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [Status](./core.status.md)

## Status enum

Status codes returned by the Cerbos policy decision point server.

**Signature:**

```typescript
export declare enum Status 
```

## Enumeration Members

|  Member | Value | Description |
|  --- | --- | --- |
|  CANCELLED | <code>1</code> | The operation was cancelled. |
|  DEADLINE\_EXCEEDED | <code>4</code> | The operation timed out. |
|  INTERNAL | <code>13</code> | The operation failed due to an internal error. |
|  INVALID\_ARGUMENT | <code>3</code> | The operation was rejected because an argument was invalid. |
|  RESOURCE\_EXHAUSTED | <code>8</code> | The operation failed because a resource has been exhausted. |
|  UNAUTHENTICATED | <code>16</code> | The operation was rejected because it did not have valid authentication credentials. |
|  UNAVAILABLE | <code>14</code> | The operation was rejected because it did not have valid authentication credentials. |
|  UNIMPLEMENTED | <code>12</code> | The operation is not supported. |
|  UNKNOWN | <code>2</code> | An unknown error occurred. |

