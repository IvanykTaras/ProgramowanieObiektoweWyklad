>[link to microsoft documentation](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

# Naming conventions
## Use pascal for 

`class, record, struct`
```
public class DataService
public record PhysicalAddress
public struct ValueCoordinate
```
`interface` use with prefix I
```
public interface IWorkerQueue
```
`public members of types` (properties, events, methods, and local functions)

```
public bool IsValid
```
---
## Camel case

`private, internal` fields with prefix _
```
private IWorkerQueue _workerQueue
```

`static private, static internal` fileds with prefix s_ threat with t_
```
private static IWorkerQueue s_workerQueue
private static TimeSpan t_timeSpan
```

`method parameters`
```
public T SomeMethod<T>(int someNumber, bool isValid)
```
---
---
# Additional naming conventions
Qualified names can be broken after a dot (.) if they are too long
```
System.Diagnostics.
PerformanceCounterCategory();
```
---
---
# Layout conventions
* Write only one statement per line.
* Write only one declaration per line.
* Add space between method `name` and property `definitions`.
```c#
public static Add (int a, int b)
```



