---
description: Acts as a mediator for executing operations and handling their results.
---

# ResultExecutor

## Namespace

`Carcass.Core`

## Methods

### **`ExecuteAsync`**

Asynchronously executes the provided function and returns a [Result](result.md) object that represents the outcome of the operation.

```csharp
public async Task<Result<TSuccess, TFailure>> ExecuteAsync<TSuccess, TFailure>(Func<Task<TSuccess>> func, Func<Exception, TFailure> exceptionHandler)
```
