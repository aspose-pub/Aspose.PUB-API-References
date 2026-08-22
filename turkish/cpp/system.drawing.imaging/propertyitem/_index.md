---
title: "System::Drawing::Imaging::PropertyItem sınıfı"
linktitle: "PropertyItem"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Imaging::PropertyItem sınıfı. Bir görüntü dosyasına dahil edilecek bir meta veri özelliğini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1400
url: /tr/cpp/system.drawing.imaging/propertyitem/
---
## PropertyItem class


Bir görüntü dosyasına dahil edilecek bir meta veri özelliğini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class PropertyItem : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Id](./get_id/)() const | Geçerli nesne tarafından temsil edilen özelliğin kimliğini (ID) döndürür. |
| [get_Len](./get_len/)() const | Geçerli nesne tarafından temsil edilen özelliğin uzunluğunu bayt cinsinden döndürür. |
| [get_Type](./get_type/)() const | Geçerli nesne tarafından temsil edilen özelliğin tipini bayt cinsinden döndürür. |
| [get_Value](./get_value/)() const | Geçerli nesne tarafından temsil edilen özelliğin değerini bayt cinsinden döndürür. |
| [PropertyItem](./propertyitem/)() | [PropertyItem](./) sınıfının yeni bir örneğini oluşturur. |
| [set_Id](./set_id/)(int32_t) | Geçerli nesne tarafından temsil edilen özelliğin kimliğini (ID) ayarlar. |
| [set_Len](./set_len/)(int32_t) | Geçerli nesne tarafından temsil edilen özelliğin uzunluğunu bayt cinsinden ayarlar. |
| [set_Type](./set_type/)(int16_t) | Geçerli nesne tarafından temsil edilen özelliğin tipini bayt cinsinden ayarlar. |
| [set_Value](./set_value/)(const System::ArrayPtr\<uint8_t\>\&) | Geçerli nesne tarafından temsil edilen özelliğin tipini bayt cinsinden ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
