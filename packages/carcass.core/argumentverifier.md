---
description: Provides a declarative way of validating method arguments.
---

# ArgumentVerifier

## Namespace

Carcass.Core

## Methods

### **`NotNull`**

Checks if the given value is not null or whitespace.

```csharp
public static void NotNull<T>(
    T? argument,
    string argumentName,
    bool skipStringWhiteSpace = default
) where T : class
```

### **`NotDefault`**

Checks if the given value is not the default value for its type.

```csharp
public static void NotDefault<T>(T argument, string argumentName) where T : struct
```

### **`NotReadOnly`**

Checks if the given collection is not read-only.

```csharp
public static void NotReadOnly<T>(ICollection<T> argument, string argumentName)
```

### **`Requires`**

Checks if the given expression is true. If not, throws an exception with the provided message.

```csharp
public static void Requires(bool expression, string message)
```

### **`Requires`**

Checks if the given expression (provided as a `Func<bool>`) is true. If not, throws an exception with the provided message.

```csharp
public static void Requires(Func<bool> expression, string message)
```
