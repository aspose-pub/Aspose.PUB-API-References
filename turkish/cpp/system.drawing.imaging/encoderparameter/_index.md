---
title: "System::Drawing::Imaging::EncoderParameter sınıfı"
linktitle: "EncoderParameter"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Imaging::EncoderParameter sınıfı. Görüntü kodlayıcıya değerleri iletmek için kullanılan bir kapsayıcı görevi görür. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya new operatörüyle bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 600
url: /tr/cpp/system.drawing.imaging/encoderparameter/
---
## EncoderParameter class


Görüntü kodlayıcıya değerleri iletmek için kullanılan bir kapsayıcı görevi görür. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya new operatörüyle bu tipin örneğini oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class EncoderParameter : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [EncoderParameter](./encoderparameter/)() | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, uint8_t, bool) | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int16_t) | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t) | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t) | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t) | [EncoderParameter](./) sınıfının kesir temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t, int64_t) | [EncoderParameter](./) sınıfının tam sayı değerleri aralığını temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) | [EncoderParameter](./) sınıfının kesir aralığını temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const String\&) | [EncoderParameter](./) sınıfının yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) | [EncoderParameter](./) sınıfının değerler dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) | [EncoderParameter](./) sınıfının değerler dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) | [EncoderParameter](./) sınıfının değerler dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | [EncoderParameter](./) sınıfının kesirler dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) | [EncoderParameter](./) sınıfının tam sayı aralıkları dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | [EncoderParameter](./) sınıfının kesir aralıkları dizisini temsil eden yeni bir örneğini oluşturur. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) | [EncoderParameter](./) sınıfının belirtilen tampondan okunan, belirtilen tipteki belirtilen sayıda değeri temsil eden yeni bir örneğini oluşturur. |
| [get_Encoder](./get_encoder/)() const | Mevcut [EncoderParameter](./) nesnesiyle ilişkili [Encoder](../encoder/) nesnesini döndürür. |
| [get_NumberOfValues](./get_numberofvalues/)() const | Mevcut nesne tarafından temsil edilen değer sayısını döndürür. |
| [get_Type](./get_type/)() const | Mevcut nesne tarafından temsil edilen değer(ler)in tipini döndürür. |
| [set_Encoder](./set_encoder/)(const EncoderPtr\&) | Belirtilen [Encoder](../encoder/) nesnesini mevcut [EncoderParameter](./) nesnesiyle ilişkilendirir. |
| [~EncoderParameter](./~encoderparameter/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
