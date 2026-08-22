---
title: "PubException"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "يمثل الأخطاء التي تحدث أثناء تنفيذ تطبيق PUB."
type: docs
weight: 11
url: /ar/java/com.aspose.pub.exceptions/pubexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException
```
public class PubException extends System.ApplicationException
```

يمثل الأخطاء التي تحدث أثناء تنفيذ تطبيق PUB.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PubException(String message)](#PubException-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [PubException](../../com.aspose.pub.exceptions/pubexception). |
| [PubException(String message, Throwable innerException)](#PubException-java.lang.String-java.lang.Throwable-) | ينشئ مثيلاً جديدًا من الفئة [PubException](../../com.aspose.pub.exceptions/pubexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMessage()](#getMessage--) | يحصل على رسالة تصف الاستثناء الحالي. |
### PubException(String message) {#PubException-java.lang.String-}
```
public PubException(String message)
```


ينشئ مثيلاً جديدًا من الفئة [PubException](../../com.aspose.pub.exceptions/pubexception).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | الرسالة. |

### PubException(String message, Throwable innerException) {#PubException-java.lang.String-java.lang.Throwable-}
```
public PubException(String message, Throwable innerException)
```


ينشئ مثيلاً جديدًا من الفئة [PubException](../../com.aspose.pub.exceptions/pubexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة الخطأ التي تشرح سبب الاستثناء. |
| innerException | java.lang.Throwable | الاستثناء الذي هو سبب الاستثناء الحالي، أو إشارة فارغة (Nothing في Visual Basic) إذا لم يتم تحديد استثناء داخلي. |

### getMessage() {#getMessage--}
```
public String getMessage()
```


يحصل على رسالة تصف الاستثناء الحالي.

**Returns:**
java.lang.String
