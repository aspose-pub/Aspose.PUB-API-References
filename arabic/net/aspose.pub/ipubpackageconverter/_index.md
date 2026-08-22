---
title: "الواجهة IPubPackageConverter"
second_title: "Aspose.PUB لـ .NET مرجع API"
description: "الواجهة Aspose.Pub.IPubPackageConverter. تُعلن عن الوظيفة لتحويل مستندات Publisher متعددة إلى تنسيق محدد"
type: docs
weight: 140
url: /ar/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

يعلن عن وظيفة تحويل عدة مستندات Publisher إلى تنسيق محدد.

```csharp
public interface IPubPackageConverter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | يقوم بتحويل كل مستند من قائمة *inputDocumentCollection* إلى التنسيق المحدد ويحفظ النتائج في التخزين المناسب. نوع التخزين للحفظ يُحدد بواسطة المعامل *outputType*. تُوضع مراجع المستندات المحوّلة في الكائن [`PackageDocumentCollection`](../packagedocumentcollection/) المُعاد. إذا تم تعيين علامة *mergeFiles*، فسيتم دمج جميع المستندات المحوّلة في مستند واحد بنفس الترتيب الذي وضعت به في قائمة *inputDocumentCollection*. |

### انظر أيضًا

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


