---
title: "System::Net::Http::Headers::TransferCodingHeaderValue sınıfı"
linktitle: "TransferCodingHeaderValue"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::TransferCodingHeaderValue sınıfı. ''Accept-Encoding'' başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve C++'da fonksiyonlara argüman olarak geçirmek için bu işaretçiyi kullanın."
type: docs
weight: 2400
url: /tr/cpp/system.net.http.headers/transfercodingheadervalue/
---
## TransferCodingHeaderValue class


'Accept-Encoding' başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class TransferCodingHeaderValue : public virtual System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| [get_Parameters](./get_parameters/)() | Parametreleri döndürür. |
| [get_Value](./get_value/)() | RTTI bilgisi. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| static [GetTransferCodingLength](./gettransfercodinglength/)(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Belirtilen indeksten itibaren verilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| static [Parse](./parse/)(String) | Geçilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)() | Yeni bir örnek oluşturur. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)(String) | Yeni bir örnek oluşturur. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Geçilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
## Ayrıca Bakınız

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
