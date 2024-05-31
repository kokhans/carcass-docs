# Result

Represents the outcome of an operation, with a success status and optional data.

## Namespace

```
Carcass.Core
```

## Properties

### **`FailureData`**

Holds data related to the failure of an operation, if applicable.

```csharp
public TFailure FailureData { get; }
```

## Methods

### **`Fail`**

Creates a failed result with the given failure data.

```csharp
public static Result<TSuccess, TFailure> Fail(TFailure failureData)
```

### **`Succeed`**

Creates a successful result with the given success data.

```csharp
public static Result<TSuccess, TFailure> Succeed(TSuccess successData)
```

### **`IsFailure`**

Indicates whether the result represents a failure.

```csharp
public bool IsFailure { get; }
```

### **`IsSuccess`**

Indicates whether the result represents a success.

```csharp
public bool IsSuccess { get; }
```
