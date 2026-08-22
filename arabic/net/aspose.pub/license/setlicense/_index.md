---
title: "License.SetLicense"
second_title: "Aspose.PUB لـ .NET مرجع API"
description: "License طريقة. يمنح الترخيص للمكوّن"
type: docs
weight: 20
url: /ar/net/aspose.pub/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (البدء).

5. مورد مدمج في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مدمج في تجميع استدعاء العميل.

2. المجلد الذي يحتوي على ملف JAR لمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | Stream | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل الترخيص من تدفق.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pub](../../license/)
* assembly [Aspose.PUB](../../../)


