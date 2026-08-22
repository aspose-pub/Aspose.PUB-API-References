---
title: "الفئة Coord"
second_title: "Aspose.PUB لـ .NET مرجع API"
description: "الفئة Aspose.Pub.Utils.Coord. تم تصميم هذه الفئة لتمثيل البيانات المتعلقة بإحداثيات حقول PUB. كل حقل في PUB يحتوي على إحداثيات، لديه زوجان من الإحداثيات: إحداثيات الزاوية العلوية اليسرى XLeft YTop وإحداثيات الزاوية السفلية اليمنى XRight YBottom. جميع الإحداثيات ممثلة في نظام قياس خاص وحدة القياس الإنجليزية EMUs. تمت إضافة طرق إضافية إلى هذه الفئة لتحويل قيم الإحداثيات من وحدات القياس الإنجليزية إلى بوصات."
type: docs
weight: 350
url: /ar/net/aspose.pub.utils/coord/
---
## Coord class

تم تصميم هذه الفئة لتمثيل البيانات المتعلقة بإحداثيات حقول PUB. كل حقل في PUB يحتوي على إحداثيات تتكون من زوجين من الإحداثيات: إحداثيات الزاوية العلوية اليسرى (XLeft, YTop) وإحداثيات الزاوية السفلية اليمنى (XRight, YBottom). جميع الإحداثيات ممثلة في نظام قياس خاص - وحدة القياس الإنجليزية (EMUs). تمت إضافة طرق إضافية إلى هذه الفئة لتحويل قيم الإحداثيات من وحدات القياس الإنجليزية إلى البوصات.

```csharp
public class Coord : ICloneable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Coord](coord/#constructor)() | المنشئ |
| [Coord](coord/#constructor_1)(int, int, int, int) | المنشئ |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | الإحداثي X للزاوية العلوية اليسرى بوحدات EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | الإحداثي X للزاوية السفلية اليمنى بوحدات EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | الإحداثي Y للزاوية السفلية اليمنى بوحدات EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | الإحداثي Y للزاوية العلوية اليسرى بوحدات EMUs |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | يحسب ارتفاع الشكل (كائن Coord الحالي) ويعيد النتيجة بالبوصات |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | يحسب عرض الشكل (كائن Coord الحالي) ويعيد النتيجة بالبوصات |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | يحوّل القيمة للإحداثي X من نظام قياس PUB الطبيعي إلى البوصات |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | يحوّل القيمة للإحداثي X من نظام قياس PUB الطبيعي إلى البوصات |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | يحوّل القيمة للإحداثي Y من نظام قياس PUB الطبيعي إلى البوصات |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | يحوّل القيمة للإحداثي Y من نظام قياس PUB الطبيعي إلى البوصات |
| [Clone](../../aspose.pub.utils/coord/clone/)() | تم إنشاء نسخة من الكائن |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | يعيد ارتفاع كائن Coord الحالي بمقاييس PUB الطبيعية |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | يعيد عرض كائن Coord الحالي بمقاييس PUB الطبيعية |

### انظر أيضًا

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


