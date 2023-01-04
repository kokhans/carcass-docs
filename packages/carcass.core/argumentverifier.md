# ArgumentVerifier

`ArgumentVerifier` provides a declarative way of validating method arguments.

## NotNull

Check if the given value is not null or whitespace.

```csharp
public static void NotNull<T>(
    T? argument,
    string argumentName,
    bool skipStringWhiteSpace = default
) where T : class
```

## NotDefault

Check if the given value is not default.&#x20;

```csharp
public static void NotDefault<T>(T argument, string argumentName) where T : struct
```

## NotDefault

Check if the given value is not read-only.

```csharp
public static void NotReadOnly<T>(ICollection<T> argument, string argumentName)
```
