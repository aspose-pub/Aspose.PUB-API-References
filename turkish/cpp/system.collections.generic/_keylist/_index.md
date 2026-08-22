---
title: "System::Collections::Generic::_KeyList sınıfı"
linktitle: "_KeyList"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::_KeyList sınıfı. Sözlüğün anahtarlarının listesini uygular. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 200
url: /tr/cpp/system.collections.generic/_keylist/
---
## _KeyList class


Dictionary'nin anahtarlarının listesini uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```


| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [_KeyList](./_keylist/)(const typename Dict::Ptr\&) | Belirtilen sözlüğe referans veren koleksiyonu başlatır. |
| [Contains](./contains/)(const TKey\&) const override | Belirtilen anahtarın koleksiyonda bulunup bulunmadığını kontrol eder. |
| [idx_get](./idx_get/)(int) const override | Belirtilen konumdaki anahtarı alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [TKey](./tkey/) | Anahtar türü. |

## Ayrıca Bakınız

* Class [_KeyCollection](../_keycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
