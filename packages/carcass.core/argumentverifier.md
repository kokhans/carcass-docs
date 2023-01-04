# ArgumentVerifier

`ArgumentVerifier` provides a declarative way of validating method arguments.

## NotNull

```csharp
public static void NotNull<T>(
    T? argument,
    string argumentName,
    bool skipStringWhiteSpace = default
) where T : class
```

Check if the given value is not null or whitespace.

## NotDefault

```csharp
public static void NotDefault<T>(T argument, string argumentName) where T : struct
```

Check if the given value is not default.&#x20;

## NotDefault

```csharp
public static void NotReadOnly<T>(ICollection<T> argument, string argumentName)
```

Check if the given value is not read-only.
