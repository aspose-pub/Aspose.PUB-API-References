---
title: "System::Collections::Generic::_ValueList sınıfı"
linktitle: "_ValueList"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::_ValueList sınıfı. Sözlüğün değerlerinin listesini uygular. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu türün bir örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 400
url: /tr/cpp/system.collections.generic/_valuelist/
---
## _ValueList class


Sözlüğün değerlerinin listesini uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu türün bir örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
template<typename Dict>class _ValueList : public System::Collections::Generic::_ValueCollection<Dict>
```


| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [_ValueList](./_valuelist/)(const typename Dict::Ptr\&) | Belirtilen sözlüğe referans veren koleksiyonu başlatır. |
| virtual [idx_get](./idx_get/)(int) const | Belirtilen konumdaki değeri alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [TValue](./tvalue/) | Değer türü. |

## Ayrıca Bakınız

* Class [_ValueCollection](../_valuecollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
