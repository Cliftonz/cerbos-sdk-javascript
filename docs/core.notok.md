<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@cerbos/core](./core.md) &gt; [NotOK](./core.notok.md)

## NotOK class

Error thrown when the Cerbos policy decision point server returns an unsuccessful response.

**Signature:**

```typescript
export declare class NotOK extends Error 
```
**Extends:** Error

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(code, details)](./core.notok._constructor_.md) |  | Constructs a new instance of the <code>NotOK</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [code](./core.notok.code.md) | <code>readonly</code> | [Status](./core.status.md) | The status code returned by the Cerbos policy decision point server. |
|  [details](./core.notok.details.md) | <code>readonly</code> | string | Additional error details. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [fromJSON(text)](./core.notok.fromjson.md) | <code>static</code> | Parse a JSON-serialized unsuccessful response. |

