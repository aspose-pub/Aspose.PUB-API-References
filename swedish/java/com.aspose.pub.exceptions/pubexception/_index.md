---
title: "PubException"
second_title: "Aspose.PUB för Java API-referens"
description: "Representerar fel som uppstår under PUB-applikationskörning."
type: docs
weight: 11
url: /sv/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

Representerar fel som uppstår under PUB-applikationskörning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | Initierar en ny instans av klassen [PubException](../../com.aspose.pub.exceptions/pubexception). |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | Initierar en ny instans av klassen [PubException](../../com.aspose.pub.exceptions/pubexception) med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMessage()](#getMessage--) | Hämtar ett meddelande som beskriver det aktuella undantaget. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


Initierar en ny instans av klassen [PubException](../../com.aspose.pub.exceptions/pubexception).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


Initierar en ny instans av klassen [PubException](../../com.aspose.pub.exceptions/pubexception) med ett specificerat felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Felmeddelandet som förklarar orsaken till undantaget. |
| innerException | java.lang.Throwable | Undantaget som är orsaken till det aktuella undantaget, eller en null-referens (Nothing i Visual Basic) om inget inre undantag har angetts. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Hämtar ett meddelande som beskriver det aktuella undantaget.

**Returns:**
java.lang.String
