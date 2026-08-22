---
title: "System::Net::Http::Headers::HttpHeaders sınıfı"
linktitle: "HttpHeaders"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::HttpHeaders sınıfı. HTTP başlıklarının koleksiyonudur. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 700
url: /tr/cpp/system.net.http.headers/httpheaders/
---
## HttpHeaders class


HTTP başlıklarının koleksiyonudur. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class HttpHeaders : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Collections::Generic::IEnumerable<System::String>>>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Yeni bir ad-değer çifti doğrular ve mevcut koleksiyona ekler. |
| [Add](./add/)(String, String) | Yeni bir ad-değer çifti doğrular ve mevcut koleksiyona ekler. |
| virtual [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) | Belirtilen HttpHeaders sınıfı örneğini mevcut olanla birleştirir. |
| [AddParsedValue](./addparsedvalue/)(String, System::SharedPtr\<Object\>) | Belirtilen adla bir başlık alır ve ayrıştırılmış bir değeri başlığa ekler. |
| [Clear](./clear/)() | Koleksiyondaki tüm öğeleri kaldırır. |
| [Contains](./contains/)(String) |  |
| [ContainsParsedValue](./containsparsedvalue/)(String, System::SharedPtr\<Object\>) | Başlığın belirtilen değeri içerip içermediğini kontrol eder. |
| [GetEnumerator](./getenumerator/)() override | Yineleyiciyi alır. |
| [GetHeaderString](./getheaderstring/)(String) | Belirtilen başlık adıyla değerlerin dize temsilini döndürür. |
| [GetHeaderString](./getheaderstring/)(String, System::SharedPtr\<Object\>) | Belirtilen başlık adıyla değerlerin dize temsilini döndürür. |
| [GetHeaderStrings](./getheaderstrings/)() | Başlıkların değerlerinin dize temsillerini içeren bir koleksiyon döndürür. |
| [GetParsedValues](./getparsedvalues/)(String) | Belirtilen başlık adıyla ayrıştırılmış değerleri döndürür. |
| [GetValues](./getvalues/)(String) | Belirtilen adla ilgili değerleri döndürür. |
| static [ParsedValuesAsList](./parsedvaluesaslist/)(const System::SharedPtr\<Object\>) | Ayrıştırılmış değerleri listeye dönüştürür. |
| [Remove](./remove/)(String) | Belirtilen adla bir öğeyi kaldırmaya çalışır. |
| [RemoveParsedValue](./removeparsedvalue/)(String, System::SharedPtr\<Object\>) | Belirtilen adla bir başlığı alır ve başlıktan ayrıştırılmış bir değeri kaldırır. |
| [SetConfiguration](./setconfiguration/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, System::SharedPtr\<HttpHeaderParser\>\>\>, System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) |  |
| [SetOrRemoveParsedValue](./setorremoveparsedvalue/)(String, System::SharedPtr\<Object\>) | Belirtilen adla bir başlığı alır ve değerini ayarlar veya kaldırır. 'value' parametresi nullptr olduğunda başlık değeri kaldırılacak, aksi takdirde ayrıştırılmış bir değer ayarlanacaktır. |
| [SetParsedValue](./setparsedvalue/)(String, System::SharedPtr\<Object\>) | Belirtilen adla bir başlığı alır ve başlığa ayrıştırılmış bir değer ayarlar. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, String) | Mevcut koleksiyona yeni bir ad-değer çifti eklemeye çalışır. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Mevcut koleksiyona ad-değer çiftleri koleksiyonu ekler. |
| [TryGetValues](./trygetvalues/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) | Belirtilen adla ilgili değerleri almaya çalışır. |
| [TryParseAndAddValue](./tryparseandaddvalue/)(String, String) | Belirtilen değeri ayrıştırmaya çalışır ve başlık değerlerine ekler. |
## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
