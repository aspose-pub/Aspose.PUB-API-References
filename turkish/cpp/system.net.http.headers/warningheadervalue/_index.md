---
title: "System::Net::Http::Headers::WarningHeaderValue sınıfı"
linktitle: "WarningHeaderValue"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::WarningHeaderValue sınıfı. ''Warning'' başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Yığın (stack) üzerinde veya new operatörüyle örnek oluşturmaktan kaçının, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve C++'ta fonksiyonlara argüman olarak bu işaretçiyi geçirin."
type: docs
weight: 2700
url: /tr/cpp/system.net.http.headers/warningheadervalue/
---
## WarningHeaderValue class


‘Warning’ başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Yığın üzerinde veya new operatörüyle örnek oluşturmaktan kaçının, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class WarningHeaderValue : public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| [get_Agent](./get_agent/)() | Uyarıya ekli ana bilgisayarı döndürür. |
| [get_Code](./get_code/)() | RTTI bilgisi. |
| [get_Date](./get_date/)() | Uyarının tarih ve saatini döndürür. |
| [get_Text](./get_text/)() | Uyarı metnini döndürür. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| static [GetWarningLength](./getwarninglength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Belirtilen indeksden başlayan geçilen bir dizeyi [WarningHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| static [Parse](./parse/)(String) | Geçilen bir dizeyi [WarningHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<WarningHeaderValue\>\&) | Geçilen bir dizeyi [WarningHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String) | Yeni bir örnek oluşturur. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String, DateTimeOffset) | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
