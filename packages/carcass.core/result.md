# Result

Represents the outcome of an operation, with a success status and optional data.

## Namespace

`Carcass.Core`

## Properties

### **`Payload`**

The result of the operation if it was successful.

```csharp
public T? Payload { get; private set; }
```

### **`FailureReason`**

A string explaining why the operation failed.

```csharp
public string? FailureReason { get; private set; }
```

### **`FailureException`**

An exception that was thrown during the operation.

```csharp
public Exception? FailureException { get; private set; }
```

### **`FailureData`**

Additional data about the failure.

```csharp
public KeyValuePair<Type, object>? FailureData { get; private set; }
```

### **`IsSuccess`**

A boolean indicating whether the operation was successful.

```csharp
public bool IsSuccess { get; }
```

## Methods

### **`Fail`**

Creates a failed result with the given failure data.

```csharp
public static Result<T> Fail(
        Exception? failureException = default,
        string? failureReason = default,
        Type? failureType = default,
        object? failureData = default
    )
```

### **`Success`**

Creates a successful result with the given success data.

```csharp
public static Result<T> Success(T? payload)
```
