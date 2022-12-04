---
title: ServiceException constructor (1 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class.

```csharp
public ServiceException()
```

## See Also

* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceException constructor (2 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class with a specified error code.

```csharp
public ServiceException(ServiceError error)
```

| parameter | description |
| --- | --- |
| error | The error code of the error that occurred. |

## See Also

* enum [ServiceError](../ServiceError.md)
* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceException constructor (3 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class with a specified error message.

```csharp
public ServiceException(string message)
```

| parameter | description |
| --- | --- |
| message | The message that describes the error. |

## See Also

* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceException constructor (4 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class with serialized data.

```csharp
protected ServiceException(SerializationInfo info, StreamingContext context)
```

| parameter | description |
| --- | --- |
| info | The SerializationInfo that holds the serialized object data about the exception being thrown. |
| context | The StreamingContext that contains contextual information about the source or destination. |

## See Also

* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceException constructor (5 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class with a specified error code and error message.

```csharp
public ServiceException(ServiceError error, string message)
```

| parameter | description |
| --- | --- |
| error | The error code of the error that occurred. |
| message | A message which describes the error. |

## See Also

* enum [ServiceError](../ServiceError.md)
* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceException constructor (6 of 6)
---

Initializes a new instance of the [`ServiceException`](../ServiceException.md) class with a specified error message and a reference to the inner exception that is the cause of this exception.

```csharp
public ServiceException(string message, Exception inner)
```

| parameter | description |
| --- | --- |
| message | The error message that explains the reason for the exception. |
| inner | The exception that is the cause of the current exception, or `null` if no inner exception is specified. |

## See Also

* class [ServiceException](../ServiceException.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->