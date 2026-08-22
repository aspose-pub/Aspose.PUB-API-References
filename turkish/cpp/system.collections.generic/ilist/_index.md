---
title: "System::Collections::Generic::IList class"
linktitle: "IList"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::IList sınıfı. Öğelerin indeksli konteynerinin arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2600
url: /tr/cpp/system.collections.generic/ilist/
---
## IList class


Öğelerin indeksli konteynerinin arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class IList : public System::Collections::Generic::ICollection<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsFixedSize](./get_isfixedsize/)() | Koleksiyonun sabit boyutta olup olmadığını kontrol eder. |
| virtual [idx_get](./idx_get/)(int) const | Belirtilen indeksteki öğeyi alır. |
| virtual [idx_set](./idx_set/)(int, T) | Belirtilen indeksteki öğeyi ayarlar. |
| virtual [IndexOf](./indexof/)(const T\&) const | Öğenin kapsayıcıda ilk ortaya çıkışının dizinini alır. |
| virtual [Insert](./insert/)(int, const T\&) | Elemanı belirtilen konuma ekler, diğer elemanları kaydırır. |
| virtual [RemoveAt](./removeat/)(int) | Belirtilen indeksteki öğeyi kaldırır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | RTTI bilgisi. |
| [ThisType](./thistype/) | Bu tip. |
| [ValueType](./valuetype/) | Değer türü. |

## Ayrıca Bakınız

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
