---
title: "System::Drawing::Imaging::Metafile sınıfı"
linktitle: "Metafile"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Imaging::Metafile sınıfı. Grafik metafileyi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 1200
url: /tr/cpp/system.drawing.imaging/metafile/
---
## Metafile class


Grafik metafileyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class Metafile : public System::Drawing::Image
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() override | Mevcut nesnenin bir kopyasını döndürür. |
| [get_Height](./get_height/)() const override | Görüntünün yüksekliğini piksel cinsinden döndürür. |
| [get_PixelFormat](./get_pixelformat/)() const override | Piksel biçimini gösteren bir değer döndürür. |
| [get_RawFormat](./get_rawformat/)() const override | Görüntü biçimini gösteren bir değer döndürür. |
| [get_Width](./get_width/)() const override | Görüntünün genişliğini piksel olarak döndürür. |
| [GetHenhmetafile](./gethenhmetafile/)() | UYGULANMADI. |
| [GetMetafileHeader](./getmetafileheader/)() | Mevcut nesneyle ilişkili bir başlığı döndürür. |
| [Metafile](./metafile/)(const System::String\&) | UYGULANMADI. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&) | UYGULANMADI. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, EmfType) | UYGULANMADI. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr) | UYGULANMADI. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, Rectangle, MetafileFrameUnit, EmfType) | UYGULANMADI. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, RectangleF, MetafileFrameUnit, EmfType) | UYGULANMADI. |
| [Metafile](./metafile/)(IntPtr, EmfType) | UYGULANMADI. |
| [PlayRecord](./playrecord/)(EmfPlusRecordType, int32_t, int32_t, System::ByteArrayPtr) | UYGULANMADI. |
| virtual [~Metafile](./~metafile/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Image](../../system.drawing/image/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
