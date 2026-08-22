---
title: "رخصة"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 14
url: /ar/java/com.aspose.pub/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن.

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على الـ component، في المجلد الذي يحتوي على الـ calling assembly، في مجلد الـ entry assembly، ثم في الموارد المضمنة للـ calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [License()](#License--) | يُهيئ نسخة جديدة من هذه الفئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | بشكل افتراضي نستخدم أمان jdk الافتراضي. |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | بشكل افتراضي، نستخدم أمان jre الافتراضي. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
### License() {#License--}
```
public License()
```


يُهيئ نسخة جديدة من هذه الفئة.

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على الـ component، في المجلد الذي يحتوي على الـ calling assembly، في مجلد الـ entry assembly، ثم في الموارد المضمنة للـ calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


بشكل افتراضي نستخدم أمان jdk الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا.

**Returns:**
boolean - قيمة boolean
### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


بشكل افتراضي، نستخدم أمان jre الافتراضي. القيمة الافتراضية == false. في بعض الحالات لا يمكن لبيئة جافا المخصصة دعم الخوارزميات المطلوبة، لذا يمكننا اقتراح استخدام أمان FIPS المدمج داخليًا. لاحظ أيضًا: وفقًا لخوارزمية JVM SecureRandom على بعض أنظمة التشغيل ينتظر /dev/random كمية معينة من \u201cnoise\u201d لتُولد على الجهاز المضيف قبل إرجاع النتيجة. المكتبة المستخدمة لتوليد الأرقام العشوائية في JVM الخاص بـ Oracle تعتمد على /dev/random بشكل افتراضي لمنصات UNIX. على الرغم من أن /dev/random أكثر أمانًا، يُنصح باستخدام /dev/urandom إذا كان تكوين JVM الافتراضي يتسبب في تأخيرات، أو إضافة أجهزة تولد إنتروبيا لـ /dev/random. خيار جافا التالي يمكن أن يساعد في تجنب التأخيرات وتجاوز إعداد securerandom.source. -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| internalFIPSSecurity | منطقي | قيمة منطقية |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


يرخص المكوّن.

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. مجلد ملف jar الخاص بالـ component.

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على الـ component، في المجلد الذي يحتوي على الـ calling assembly، في مجلد الـ entry assembly، ثم في الموارد المضمنة للـ calling assembly.

License license = new License();
license.setLicense("MyLicense.lic");

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | java.lang.String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


يرخص المكوّن.

دفق يحتوي على الترخيص.

استخدم هذه الطريقة لتحميل الترخيص من دفق.

License license = new License();
license.setLicense(myStream);

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | java.io.InputStream | دفق الترخيص |

