---
title: "System::Drawing::ImageConverter sınıfı"
linktitle: "ImageConverter"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::ImageConverter sınıfı. Image nesnelerini bir veri tipinden diğerine dönüştürür. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1300
url: /tr/cpp/system.drawing/imageconverter/
---
## ImageConverter class


Converts [Image](../image/) nesnelerini bir veri tipinden diğerine dönüştürür. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Nesneyi belirli bir tipe dönüştürür. |
| [ImageConverter](./imageconverter/)() | [ImageConverter](./) sınıfının yeni bir örneğini oluşturur. |
## Ayrıca Bakınız

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
