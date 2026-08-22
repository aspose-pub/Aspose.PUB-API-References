---
title: "System::Text::ASCIIEncoding sınıfı"
linktitle: "ASCIIEncoding"
second_title: "Aspose.PUB için C++"
description: "System::Text::ASCIIEncoding sınıfı. ASCII kodlamasını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 100
url: /tr/cpp/system.text/asciiencoding/
---
## ASCIIEncoding class


ASCII kodlamasını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ASCIIEncoding](./asciiencoding/)() | Yapıcı. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Bilinen karakter sayısına sahip bir dizeyi tutabilecek maksimum bayt sayısını alır. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Belirtilen sayıda baytı çözümlemek için gereken azami karakter sayısını al. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Varsayılan kod sayfası değeri. |
## Ayrıca Bakınız

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
