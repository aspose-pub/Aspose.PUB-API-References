---
title: "System::Net::Http::StringContent sınıfı"
linktitle: "StringContent"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::StringContent sınıfı. HTTP içeriğini bir dize olarak temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1100
url: /tr/cpp/system.net.http/stringcontent/
---
## StringContent class


HTTP içeriğini bir dize olarak temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class StringContent : public System::Net::Http::ByteArrayContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [StringContent](./stringcontent/)(String) | RTTI bilgisi. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>) | Yeni bir örnek oluşturur. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>, String) | Yeni bir örnek oluşturur. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Varsayılan kodlama. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Maksimum bayt sayısı. |
## Ayrıca Bakınız

* Class [ByteArrayContent](../bytearraycontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
