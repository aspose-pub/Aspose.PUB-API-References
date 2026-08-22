---
title: "System::Net::Http::Headers::ContentRangeHeaderValue sınıfı"
linktitle: "ContentRangeHeaderValue"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::ContentRangeHeaderValue sınıfı. ''Content-Range'' başlığının değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 400
url: /tr/cpp/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue class


''Content-Range'' başlığının değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t, int64_t) | Yeni bir örnek oluşturur. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t) | Yeni bir örnek oluşturur. |
| [ContentRangeHeaderValue](./contentrangeheadervalue/)(int64_t, int64_t) | Yeni bir örnek oluşturur. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| [get_From](./get_from/)() | Veri gönderiminin başlaması gereken konumu alır. |
| [get_HasLength](./get_haslength/)() const | Geçerli başlık için uzunluğun belirtilip belirtilmediğini gösteren bir değeri alır. |
| [get_HasRange](./get_hasrange/)() const | Geçerli başlık için aralığın belirtilip belirtilmediğini gösteren bir değeri alır. |
| [get_Length](./get_length/)() | Bir varlık gövdesinin uzunluğunu alır. |
| [get_To](./get_to/)() | Veri gönderiminin durması gereken konumu alır. |
| [get_Unit](./get_unit/)() | RTTI bilgisi. |
| static [GetContentRangeLength](./getcontentrangelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Geçilen dizeyi belirtilen konumdan [ContentRangeHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| static [Parse](./parse/)(String) | Geçilen dizeyi [ContentRangeHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [set_Unit](./set_unit/)(String) | Aralıkta kullanılan birimleri ayarlar. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) | Geçilen dizeyi [ContentRangeHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
## Ayrıca Bakınız

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
