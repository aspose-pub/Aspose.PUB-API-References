---
title: "PubException"
second_title: "Aspose.PUB для Java справочник API"
description: "Представляет ошибки, возникающие во время выполнения приложения PUB."
type: docs
weight: 11
url: /ru/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

Представляет ошибки, возникающие во время выполнения приложения PUB.
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | Инициализирует новый экземпляр класса [PubException](../../com.aspose.pub.exceptions/pubexception). |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса [PubException](../../com.aspose.pub.exceptions/pubexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной данного исключения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getMessage()](#getMessage--) | Получает сообщение, описывающее текущее исключение. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


Инициализирует новый экземпляр класса [PubException](../../com.aspose.pub.exceptions/pubexception).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


Инициализирует новый экземпляр класса [PubException](../../com.aspose.pub.exceptions/pubexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной данного исключения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке, объясняющее причину исключения. |
| innerException | java.lang.Throwable | Исключение, являющееся причиной текущего исключения, или нулевая ссылка (Nothing в Visual Basic), если внутреннее исключение не указано. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Получает сообщение, описывающее текущее исключение.

**Returns:**
java.lang.String
