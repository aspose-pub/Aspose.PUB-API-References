---
title: "System::Drawing::Imaging::ImageFormat class"
linktitle: "ImageFormat"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Imaging::ImageFormat sınıfı. Bir görüntünün dosya biçimini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1100
url: /tr/cpp/system.drawing.imaging/imageformat/
---
## ImageFormat class


Bir görüntünün dosya biçimini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ImageFormat : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(ImageFormatPtr) const | Geçerli ve belirtilen nesneler tarafından temsil edilen görüntü biçimlerinin eşit olup olmadığını belirler. |
| static [get_Bmp](./get_bmp/)() | Bitmap görüntü biçimini temsil eden bir [ImageFormat](./) nesnesine ortak göstergeci döndürür. |
| static [get_Emf](./get_emf/)() | Gelişmiş metafile biçimini temsil eden bir [ImageFormat](./) nesnesine ortak göstergeci döndürür. |
| static [get_Exif](./get_exif/)() | Değiştirilebilir [Image](../../system.drawing/image/) Dosyası (Exif) biçimini temsil eden bir [ImageFormat](./) nesnesine ortak göstergeci döndürür. |
| static [get_Gif](./get_gif/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi [Graphics](../../system.drawing/graphics/) Değişim Formatı (GIF) görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| [get_Guid](./get_guid/)() const | Geçerli nesne tarafından temsil edilen görüntü formatıyla ilişkili GUID'i döndürür. |
| static [get_Icon](./get_icon/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi [Windows](../../system.windows/) simge görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| static [get_Jpeg](./get_jpeg/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi Joint Photographic Experts Group (JPEG) görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| static [get_MemoryBmp](./get_memorybmp/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi bellekteki bir bitmap'in formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| static [get_Png](./get_png/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi W3C Taşınabilir Ağ [Graphics](../../system.drawing/graphics/) (PNG) görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| static [get_Tiff](./get_tiff/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi Etiketli [Image](../../system.drawing/image/) Dosya Formatı (TIFF) görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| static [get_Wmf](./get_wmf/)() | Paylaşımlı bir işaretçi döndürür, bu işaretçi [Windows](../../system.windows/) metafile (WMF) görüntü formatını temsil eden bir [ImageFormat](./) nesnesidir. |
| [ImageFormat](./imageformat/)(const System::Guid\&) | Belirtilen GUID ile ilişkili bir görüntü formatı formatını temsil eden [ImageFormat](./) sınıfının bir örneğini oluşturur. |
| virtual [ToString](./tostring/)() const | Bu [ImageFormat](./) nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
