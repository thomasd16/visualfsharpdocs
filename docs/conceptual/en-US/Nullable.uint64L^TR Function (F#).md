# Nullable.uint64<^T> Function (F#)

Converts the argument to unsigned 64-bit integer ([uint64](http://msdn.microsoft.com/en-us/library/3c4f3a04-06eb-48aa-b38e-16646bda2f33)). This is a direct conversion for all primitive numeric types. The operation requires an appropriate static conversion method on the input type.

**Namespace/Module Path**: Microsoft.FSharp.Linq.Nullable

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
uint64 : Nullable<^T> -> Nullable<uint64> when ^T with static member op_Explicit and ^T : (new : unit ->  ^T) and ^T : struct and ^T :> ValueType

// Usage:
Nullable.uint64 value
```

#### CAPS_PARAMETERS_MD
*value*
Type: **T:System.Nullable&#96;1**&lt;^T&gt;


The input value.




## Return Value
The converted uint64.


## CAPS_REMARKS_MD
This function is named **ToUInt64** in the .NET assembly. If accessing the member from a .NET language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.Nullable Module &#40;F&#35;&#41;](Linq.Nullable+Module+%28F%23%29.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq+Namespace+%28F%23%29.md)

[Operators.uint64&#60;^T&#62; Function &#40;F&#35;&#41;](Operators.uint64L%5ETR+Function+%28F%23%29.md)
