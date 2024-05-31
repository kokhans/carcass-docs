---
description: Provides high-performance logging mechanism over Microsoft.Extensions.Logging
---

# LoggerAdapter

## Namespace

`Carcass.Logging.Core.Adapters`

## Methods

Each method logs a message with a format string and a varying number of arguments. The format string can contain placeholders (like `{0}`, `{1}`, etc.) that will be replaced by the arguments when the message is logged.

### **`LogTrace`**

Log a trace message.

```csharp
public void LogTrace(string message)
```

Log a trace message with one argument.

```csharp
public void LogTrace<T1>(
        string formatString,
        T1 arg1
    )
```

Log a trace message with two arguments.

```csharp
public void LogTrace<T1, T2>(
        string formatString,
        T1 arg1,
        T2 arg2
    )
```

Log a trace message with three arguments.

```csharp
public void LogTrace<T1, T2, T3>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3
    )
```

Log a trace message with four arguments.

```csharp
public void LogTrace<T1, T2, T3, T4>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4
    )
```

Log a trace message with five arguments.

```csharp
public void LogTrace<T1, T2, T3, T4, T5>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4,
        T5 arg5
    )
```

Log a trace message with six arguments.

```csharp
public void LogTrace<T1, T2, T3, T4, T5, T6>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4,
        T5 arg5,
        T6 arg6
    )
```

### **`LogDebug`**

Log a debug message.

```csharp
public void LogDebug(string message)
```

Log a debug message with one argument.

```csharp
public void LogDebug<T1>(
        string formatString,
        T1 arg1
    )
```

Log a debug message with two arguments.

```csharp
public void LogDebug<T1, T2>(
        string formatString,
        T1 arg1,
        T2 arg2
    )
```

Log a debug message with three arguments.

```csharp
public void LogDebug<T1, T2, T3>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3
    )
```

Log a debug message with four arguments.

```csharp
public void LogDebug<T1, T2, T3, T4>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4
    )
```

Log a debug message with five arguments.

```csharp
public void LogDebug<T1, T2, T3, T4, T5>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4,
        T5 arg5
    )
```

Log a debug message with six arguments.

```csharp
public void LogDebug<T1, T2, T3, T4, T5, T6>(
        string formatString,
        T1 arg1,
        T2 arg2,
        T3 arg3,
        T4 arg4,
        T5 arg5,
        T6 arg6
    )
```
