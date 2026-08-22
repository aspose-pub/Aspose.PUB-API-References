---
title: "PubException"
second_title: "Referencia de API de Aspose.PUB para Java"
description: "Representa errores que ocurren durante la ejecución de la aplicación PUB."
type: docs
weight: 11
url: /es/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

Representa errores que ocurren durante la ejecución de la aplicación PUB.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | Inicializa una nueva instancia de la clase [PubException](../../com.aspose.pub.exceptions/pubexception). |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | Inicializa una nueva instancia de la clase [PubException](../../com.aspose.pub.exceptions/pubexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMessage()](#getMessage--) | Obtiene un mensaje que describe la excepción actual. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


Inicializa una nueva instancia de la clase [PubException](../../com.aspose.pub.exceptions/pubexception).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


Inicializa una nueva instancia de la clase [PubException](../../com.aspose.pub.exceptions/pubexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de error que explica la razón de la excepción. |
| innerException | java.lang.Throwable | La excepción que es la causa de la excepción actual, o una referencia nula (Nothing en Visual Basic) si no se especifica una excepción interna. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Obtiene un mensaje que describe la excepción actual.

**Returns:**
java.lang.String
