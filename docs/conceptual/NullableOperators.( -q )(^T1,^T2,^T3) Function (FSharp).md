# NullableOperators.( -? )<^T1,^T2,^T3> Function (F#)

The subtraction operator where a nullable value appears on the right.

**Namespace/Module Path**: Microsoft.FSharp.Linq.NullableOperators

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
( -? ) : ^T1 -> Nullable<^T2> -> Nullable<^T3> when ^T1 with static member (-) and ^T2 with static member (-) and ^T2 : (new : unit ->  ^T2) and ^T2 : struct and ^T2 :> ValueType and ^T3 : (new : unit ->  ^T3) and ^T3 : struct and ^T3 :> ValueType

// Usage:
-?
```

#### [!INCLUDE[System_CAPS_parameters](//System/Token/System_CAPS_parameters_md.md)]
*value*
Type: ^T1


The first input value.


*nullableValue*
Type: **T:System.Nullable&#96;1**&lt;^T2&gt;


The second input value, as a nullable value.




## Return Value
The result of the subtraction, as a nullable value.


## Remarks
If the second value is null, then the result is null.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.NullableOperators Module &#40;F&#35;&#41;](Linq.NullableOperators+Module+%28FSharp%29.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq+Namespace+%28FSharp%29.md)
