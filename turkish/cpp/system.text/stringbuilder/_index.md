---
title: "System::Text::StringBuilder sınıfı"
linktitle: "StringBuilder"
second_title: "Aspose.PUB için C++"
description: "System::Text::StringBuilder sınıfı. Dizeyi parça parça biriktirmek için tampon. Bu tür, ya değer tipi olarak yığıta ya da System::MakeObject() işlevi kullanılarak yığına tahsis edilebilir. Nesne tahsis edildikten sonra, bu iki kullanım durumunu asla karıştırmayın: yığıt üzerinde tahsis edilen nesnelere SmartPtr işaretçileri tutmak C++ içinde kesinlikle yasaktır."
type: docs
weight: 2400
url: /tr/cpp/system.text/stringbuilder/
---
## StringBuilder class


[Buffer](../../system/buffer/) to accumulate string part by part. This type can be allocated either in stack as value type or in heap using [System::MakeObject()](../../system/makeobject/) function. Once the object is allocated, never mix up these two usecases: having [SmartPtr](../../system/smartptr/) pointers onto stack-allocated objects is strictly prohibited.

```cpp
class StringBuilder : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Append](./append/)(char_t) | Builder'a karakter ekler. |
| [Append](./append/)(char_t, int) | Builder'a karakterler ekler. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&) | Builder'a karakter dizisi ekler. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&, int, int) | Builder'a karakter dizisi dilimini ekler. |
| [Append](./append/)(const String\&) | Builder'a dize ekler. |
| [Append](./append/)(const String\&, int, int) | Builder'a dize dilimini ekler. |
| [Append](./append/)(const SharedPtr\<T\>\&) | Builder'a nesnenin dize temsilini ekler. |
| [Append](./append/)(const SharedPtr\<StringBuilder\>\&) | Yapıcının içeriğini yapıcıya ekler. |
| [Append](./append/)(float) | Kayan nokta değerini yapıcıya ekler. |
| [Append](./append/)(double) | Kayan nokta değerini yapıcıya ekler. |
| [Append](./append/)(int) | Tam sayı değerini yapıcıya ekler. |
| [Append](./append/)(T) | Aritmetik değeri yapıcıya ekler. |
| [Append](./append/)(E) | Enum değerinin dize temsilini yapıcıya ekler. |
| [AppendFormat](./appendformat/)(const String\&, const TArgs\&...) | Biçimlendirilmiş dizeyi yapıcıya ekler. |
| [AppendFormat](./appendformat/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) | Biçimlendirilmiş dizeyi yapıcıya ekler. |
| [AppendLine](./appendline/)() | Yeni satır karakterini yapıcıya ekler. |
| [AppendLine](./appendline/)(const String\&) | Dizeyi yeni satır karakteriyle birlikte yapıcıya ekler. |
| [Clear](./clear/)() | Yapıcıdan tüm karakterleri kaldırır. |
| [CopyTo](./copyto/)(int, System::ArrayPtr\<char_t\> const\&, int, int) | Yapıcının verilerini mevcut dizi konumlarına kopyalar. |
| [get_Capacity](./get_capacity/)() const | Dize yapıcısının mevcut kapasitesini alır. |
| [get_Length](./get_length/)() const | Yapıcıda şu anda bulunan dize uzunluğunu alır. |
| [idx_get](./idx_get/)(int) const | Belirtilen konumdaki karakteri alır. |
| [idx_set](./idx_set/)(int, char_t) | Belirtilen konumdaki karakteri ayarlar. |
| [Insert](./insert/)(int, const String\&) | Dizeyi yapıcının sabit konumuna ekler. |
| [Insert](./insert/)(int32_t, const String\&, int32_t) | Tekrarlanan dizeyi yapıcının sabit konumuna ekler. |
| [Insert](./insert/)(int, char_t) | Karakteri yapıcının sabit konumuna ekler. |
| [Insert](./insert/)(int, const System::ArrayPtr\<char_t\>\&, int, int) | Karakterleri yapıcının sabit konumuna ekler. |
| [Insert](./insert/)(int, T) | Değeri yapıcının sabit konumuna ekler. |
| [operator[]](./operator[]/)(int) const | Belirtilen konumdaki karakteri alır. |
| [Remove](./remove/)(int, int) | Yapıcıdan parçayı kaldırır. |
| [Replace](./replace/)(const String\&, const String\&) | Yapıcı aracılığıyla alt dizeyi değiştirir. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Yapıcının aralığı üzerinden alt dizeyi değiştirir. |
| [Replace](./replace/)(char_t, char_t) | Yapıcı aracılığıyla karakteri değiştirir. |
| [Replace](./replace/)(char_t, char_t, int, int) | Yapıcının aralığı üzerinden karakteri değiştirir. |
| [set_Capacity](./set_capacity/)(int) | Dize yapıcısının mevcut kapasitesini ayarlar. |
| [set_Length](./set_length/)(int) | Dize yapıcısını belirtilen uzunluğa kırpar veya uzatır. |
| [StringBuilder](./stringbuilder/)() | Yapıcı. |
| [StringBuilder](./stringbuilder/)(int) | Yapıcı. |
| [StringBuilder](./stringbuilder/)(const String\&) | Yapıcı. |
| [StringBuilder](./stringbuilder/)(const String\&, int) | Yapıcı. |
| [StringBuilder](./stringbuilder/)(const String\&, int, int, int) | Yapıcı. |
| [ToString](./tostring/)() const override | Yapıcıda şu anda bulunan dizeyi alır. |
| [ToString](./tostring/)(int, int) const | Derleyicide şu anda bulunan alt diziyi alır. |
| [~StringBuilder](./~stringbuilder/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
