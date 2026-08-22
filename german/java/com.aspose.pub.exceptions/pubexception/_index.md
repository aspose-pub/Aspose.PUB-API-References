---
title: "PubException"
second_title: "Aspose.PUB for Java API-Referenz"
description: "Stellt Fehler dar, die während der Ausführung der PUB-Anwendung auftreten."
type: docs
weight: 11
url: /de/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

Stellt Fehler dar, die während der Ausführung der PUB-Anwendung auftreten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | Initialisiert eine neue Instanz der [PubException](../../com.aspose.pub.exceptions/pubexception) Klasse. |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | Initialisiert eine neue Instanz der [PubException](../../com.aspose.pub.exceptions/pubexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMessage()](#getMessage--) | Ruft eine Nachricht ab, die die aktuelle Ausnahme beschreibt. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


Initialisiert eine neue Instanz der [PubException](../../com.aspose.pub.exceptions/pubexception) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Nachricht. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


Initialisiert eine neue Instanz der [PubException](../../com.aspose.pub.exceptions/pubexception) Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Fehlermeldung, die den Grund für die Ausnahme erklärt. |
| innerException | java.lang.Throwable | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist, oder ein Null-Verweis (Nothing in Visual Basic), wenn keine innere Ausnahme angegeben ist. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Ruft eine Nachricht ab, die die aktuelle Ausnahme beschreibt.

**Returns:**
java.lang.String
