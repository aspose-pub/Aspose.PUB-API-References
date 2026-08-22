---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Aspose.PUB لـ .NET مرجع API"
description: "طريقة IPubPackageConverter. تقوم بتحويل كل مستند من قائمة inputDocumentCollection إلى الصيغة المحددة وتحفظ النتائج في التخزين المناسب. نوع التخزين للحفظ يُحدد بواسطة معامل outputType. تُوضع مراجع المستندات المحوّلة في كائن PackageDocumentCollection المرجع. إذا تم تعيين علامة mergeFiles فسيتم دمج جميع المستندات المحوّلة في مستند واحد بنفس الترتيب الذي وُضعت به في قائمة inputDocumentCollection."
type: docs
weight: 10
url: /ar/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

يقوم بتحويل كل مستند من قائمة *inputDocumentCollection* إلى الصيغة المحددة ويحفظ النتائج في التخزين المناسب. نوع التخزين للحفظ يُحدد بواسطة معامل *outputType*. تُوضع مراجع المستندات المحوّلة في الكائن [`PackageDocumentCollection`](../../packagedocumentcollection/) المرجع. إذا تم تعيين علامة *mergeFiles*، فسيتم دمج جميع المستندات المحوّلة في مستند واحد بنفس الترتيب الذي وُضعت به في قائمة *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | مجموعة من المستندات المدخلة. |
| mergeFiles | Boolean | يحدد ما إذا كان يجب دمج جميع مستندات الإخراج في مستند واحد. |
| outputFormat | PubExportFormats | صيغة الإخراج. |
| outputType | PubDocumentType | نوع تخزين الإخراج. |

### قيمة الإرجاع

مراجع المستندات المحوّلة في كائن [`PackageDocumentCollection`](../../packagedocumentcollection/).

### انظر أيضًا

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


