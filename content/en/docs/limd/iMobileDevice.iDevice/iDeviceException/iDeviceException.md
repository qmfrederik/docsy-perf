---
title: iDeviceException constructor (1 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class.

```csharp
public iDeviceException()
```

## See Also

* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceException constructor (2 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class with a specified error code.

```csharp
public iDeviceException(iDeviceError error)
```

| parameter | description |
| --- | --- |
| error | The error code of the error that occurred. |

## See Also

* enum [iDeviceError](../iDeviceError.md)
* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceException constructor (3 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class with a specified error message.

```csharp
public iDeviceException(string message)
```

| parameter | description |
| --- | --- |
| message | The message that describes the error. |

## See Also

* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceException constructor (4 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class with a specified error code and error message.

```csharp
public iDeviceException(iDeviceError error, string message)
```

| parameter | description |
| --- | --- |
| error | The error code of the error that occurred. |
| message | A message which describes the error. |

## See Also

* enum [iDeviceError](../iDeviceError.md)
* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceException constructor (5 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class with serialized data.

```csharp
protected iDeviceException(SerializationInfo info, StreamingContext context)
```

| parameter | description |
| --- | --- |
| info | The SerializationInfo that holds the serialized object data about the exception being thrown. |
| context | The StreamingContext that contains contextual information about the source or destination. |

## See Also

* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceException constructor (6 of 6)
---

Initializes a new instance of the [`iDeviceException`](../iDeviceException.md) class with a specified error message and a reference to the inner exception that is the cause of this exception.

```csharp
public iDeviceException(string message, Exception inner)
```

| parameter | description |
| --- | --- |
| message | The error message that explains the reason for the exception. |
| inner | The exception that is the cause of the current exception, or `null` if no inner exception is specified. |

## See Also

* class [iDeviceException](../iDeviceException.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
