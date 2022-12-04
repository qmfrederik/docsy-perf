---
title: RecoveryClientHandle constructor (1 of 2)
---

Initializes a new instance of the [`RecoveryClientHandle`](../RecoveryClientHandle.md) class.

```csharp
protected RecoveryClientHandle()
```

## See Also

* class [RecoveryClientHandle](../RecoveryClientHandle.md)
* namespace [iMobileDevice.Recovery](../../iMobileDevice-net.md)

---

---
title: RecoveryClientHandle constructor (2 of 2)
---

Initializes a new instance of the [`RecoveryClientHandle`](../RecoveryClientHandle.md) class, specifying whether the handle is to be reliably released.

```csharp
protected RecoveryClientHandle(bool ownsHandle)
```

| parameter | description |
| --- | --- |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [RecoveryClientHandle](../RecoveryClientHandle.md)
* namespace [iMobileDevice.Recovery](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->