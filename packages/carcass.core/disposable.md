---
description: Provides a mechanism to release managed/unmanaged resources.
---

# Disposable

To release managed/unmanaged resources in your application, you should inherit the `Disposable` abstract class and override methods related to the specific disposing resource type.

```csharp
public abstract class Disposable : IDisposable
```

## DisposeManagedResources

Dispose of managed resources.

```csharp
protected virtual void DisposeManagedResources()
```

## DisposeUnmanagedResources

Dispose of unmanaged resources.

```csharp
protected virtual void DisposeUnmanagedResources()
```
