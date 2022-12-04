---
title: ScreenshotrClientHandle class
---

Represents a wrapper class for Screenshotr handles.

```csharp
public class ScreenshotrClientHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](ScreenshotrClientHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](ScreenshotrClientHandle/DangerousCreate.md)(…) | Creates a new [`ScreenshotrClientHandle`](ScreenshotrClientHandle.md) from a IntPtr. (2 methods) |
| [Api](ScreenshotrClientHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](ScreenshotrClientHandle/Equals.md)(…) |  |
| override [GetHashCode](ScreenshotrClientHandle/GetHashCode.md)() |  |
| override [ToString](ScreenshotrClientHandle/ToString.md)() |  |
| [operator ==](ScreenshotrClientHandle/op_Equality.md) | Determines whether two specified instances of [`ScreenshotrClientHandle`](ScreenshotrClientHandle.md) are equal. |
| [operator !=](ScreenshotrClientHandle/op_Inequality.md) | Determines whether two specified instances of [`ScreenshotrClientHandle`](ScreenshotrClientHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [ScreenshotrClientHandle](ScreenshotrClientHandle/ScreenshotrClientHandle.md)() | Initializes a new instance of the [`ScreenshotrClientHandle`](ScreenshotrClientHandle.md) class. |
| [ScreenshotrClientHandle](ScreenshotrClientHandle/ScreenshotrClientHandle.md)(…) | Initializes a new instance of the [`ScreenshotrClientHandle`](ScreenshotrClientHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](ScreenshotrClientHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Screenshotr](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->