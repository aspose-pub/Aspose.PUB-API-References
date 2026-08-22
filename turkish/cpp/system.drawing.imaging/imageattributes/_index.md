---
title: "System::Drawing::Imaging::ImageAttributes sınıfı"
linktitle: "ImageAttributes"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Imaging::ImageAttributes sınıfı. Görüntü renklerinin render sırasında nasıl değiştirildiğine dair bilgileri temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya operator new ile oluşturulmamalıdır, aksi takdirde çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 900
url: /tr/cpp/system.drawing.imaging/imageattributes/
---
## ImageAttributes class


Görüntü renklerinin render sırasında nasıl değiştirildiğine dair bilgileri temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya operator new ile oluşturulmamalıdır, aksi takdirde çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ImageAttributes : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ClearBrushRemapTable](./clearbrushremaptable/)() | UYGULANMADI. |
| [ClearColorKey](./clearcolorkey/)(ColorAdjustType) | UYGULANMADI. |
| [ClearColorMatrix](./clearcolormatrix/)(ColorAdjustType) | UYGULANMADI. |
| [ClearGamma](./cleargamma/)(ColorAdjustType) | UYGULANMADI. |
| [ClearNoOp](./clearnoop/)(ColorAdjustType) | UYGULANMADI. |
| [ClearOutputChannel](./clearoutputchannel/)(ColorAdjustType) | UYGULANMADI. |
| [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)(ColorAdjustType) | UYGULANMADI. |
| [ClearRemapTable](./clearremaptable/)(ColorAdjustType) | UYGULANMADI. |
| [ClearThreshold](./clearthreshold/)(ColorAdjustType) | UYGULANMADI. |
| [Clone](./clone/)() | Mevcut nesnenin bir kopyasını oluşturur. |
| [Dispose](./dispose/)() | Geçerli nesne tarafından edinilen tüm işletim sistemi kaynaklarını serbest bırakır. |
| [GetAdjustedPalette](./getadjustedpalette/)(const SharedPtr\<ColorPalette\>\&, ColorAdjustType) | UYGULANMADI. |
| [ImageAttributes](./imageattributes/)() | Varsayılan yapıcı. |
| [SetBrushRemapTable](./setbrushremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&) | UYGULANMADI. |
| [SetColorKey](./setcolorkey/)(Color, Color, ColorAdjustType) | UYGULANMADI. |
| [SetColorMatrices](./setcolormatrices/)(const SharedPtr\<ColorMatrix\>\&, const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | UYGULANMADI. |
| [SetColorMatrix](./setcolormatrix/)(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | Renk ayarlama matrisini ayarlar. |
| [SetGamma](./setgamma/)(float, ColorAdjustType) | UYGULANMADI. |
| [SetNoOp](./setnoop/)(ColorAdjustType) | UYGULANMADI. |
| [SetOutputChannel](./setoutputchannel/)(ColorChannelFlag, ColorAdjustType) | UYGULANMADI. |
| [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const String\&, ColorAdjustType) | UYGULANMADI. |
| [SetRemapTable](./setremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&, ColorAdjustType) | UYGULANMADI. |
| [SetThreshold](./setthreshold/)(float, ColorAdjustType) | UYGULANMADI. |
| [SetWrapMode](./setwrapmode/)(Drawing2D::WrapMode, Color, bool) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma kipini ve rengi ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
