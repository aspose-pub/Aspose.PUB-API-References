---
title: "System::Net::Http::Headers::NameValueWithParametersHeaderValue sınıfı"
linktitle: "NameValueWithParametersHeaderValue"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::NameValueWithParametersHeaderValue sınıfı. Başlıklarda kullanılmak üzere parametreli bir anahtar/değer çifti temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da new operatörüyle oluşturmaktan kaçının; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve C++'ta fonksiyonlara argüman olarak geçirmek için bu işaretçiyi kullanın."
type: docs
weight: 1500
url: /tr/cpp/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Başlıklarda kullanılmak üzere parametreli bir anahtar/değer çifti temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) ya da new operatörüyle oluşturmaktan kaçının; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| [get_Parameters](./get_parameters/)() | RTTI bilgisi. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| static [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Belirtilen indeksden başlayan bir dizeyi [NameValueWithParametersHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String) | Yeni bir örnek oluşturur. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String, String) | Yeni bir örnek oluşturur. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Yeni bir örnek oluşturur. |
| static [Parse](./parse/)(String) | Bir dizeyi [NameValueWithParametersHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) | Geçilen bir dizeyi [NameValueWithParametersHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
## Ayrıca Bakınız

* Class [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
