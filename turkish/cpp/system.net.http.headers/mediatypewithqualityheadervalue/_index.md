---
title: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue sınıfı"
linktitle: "MediaTypeWithQualityHeaderValue"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue sınıfı. ''Content-Type'' başlığının değerinde ek kalite faktörü bulunan bir MIME tipini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1300
url: /tr/cpp/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue class


MIME türünü, 'Content-Type' başlığının değerinde ek bir kalite faktörü ile temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Yığın (stack) üzerinde veya new operatörüyle bu tipin örneği oluşturulmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Quality](./get_quality/)() | RTTI bilgisi. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Yeni bir örnek oluşturur. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String) | Yeni bir örnek oluşturur. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String, double) | Yeni bir örnek oluşturur. |
| static [Parse](./parse/)(String) | Geçilen bir dizeyi [MediaTypeWithQualityHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Bir kalite değeri ayarlar. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeWithQualityHeaderValue\>\&) | Geçilen bir dizeyi [MediaTypeWithQualityHeaderValue](./) sınıfının bir örneğine dönüştürmeyi dener. |
## Ayrıca Bakınız

* Class [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
