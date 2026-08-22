---
title: "PubException"
second_title: "Aspose.PUB for Java API Referansı"
description: "PUB uygulaması çalıştırılırken oluşan hataları temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

PUB uygulaması çalıştırılırken oluşan hataları temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | Yeni bir [PubException](../../com.aspose.pub.exceptions/pubexception) sınıfının bir örneğini başlatır. |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | Belirtilen bir hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir [PubException](../../com.aspose.pub.exceptions/pubexception) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMessage()](#getMessage--) | Mevcut istisnayı açıklayan bir mesaj alır. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


Yeni bir [PubException](../../com.aspose.pub.exceptions/pubexception) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Mesaj. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


Belirtilen bir hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir [PubException](../../com.aspose.pub.exceptions/pubexception) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İstisnanın nedenini açıklayan hata mesajı. |
| innerException | java.lang.Throwable | Mevcut istisnanın nedeni olan istisna veya iç istisna belirtilmemişse null referans (Visual Basic'te Nothing). |

### getMessage() {#getMessage--}
```
public String getMessage()
```


Mevcut istisnayı açıklayan bir mesaj alır.

**Returns:**
java.lang.String
