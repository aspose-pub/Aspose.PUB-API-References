---
title: "System::Globalization::SortKey sınıfı"
linktitle: "SortKey"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::SortKey sınıfı. Bir dizeyi sıralama anahtarına eşleme. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2200
url: /tr/cpp/system.globalization/sortkey/
---
## SortKey class


Bir dizeyi sıralama anahtarına eşleme. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class SortKey : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Compare](./compare/)(const SortKeyPtr\&, const SortKeyPtr\&) | İki sıralama anahtarını karşılaştırır. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Belirtilen nesnenin geçerli [SortKey](./) nesnesine eşit olup olmadığını denetler. |
| virtual [get_KeyData](./get_keydata/)() | Geçerli nesneyi temsil eden bayt dizisini alır. |
| virtual [get_OriginalString](./get_originalstring/)() | Bu nesneyi oluşturmak için kullanılan özgün dizeyi alır. |
| [GetHashCode](./gethashcode/)() const override | Geçerli [SortKey](./) nesnesi için karma kodunu alır. |
| [operator=](./operator=/)(const SortKey\&) |  |
| [SortKey](./sortkey/)(const SortKey\&) |  |
| [ToString](./tostring/)() const override | Geçerli nesneyi dize temsiline dönüştürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
