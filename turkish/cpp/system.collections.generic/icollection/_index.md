---
title: "System::Collections::Generic::ICollection sınıfı"
linktitle: "ICollection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::ICollection sınıfı. Öğeler koleksiyonunun arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1900
url: /tr/cpp/system.collections.generic/icollection/
---
## ICollection class


Öğeler koleksiyonunun arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Add](./add/)(const T\&) | Koleksiyona bir öğe ekler. |
| virtual [Clear](./clear/)() | Koleksiyondaki tüm öğeleri siler. |
| virtual [Contains](./contains/)(const T\&) const | Öğenin koleksiyonda bulunup bulunmadığını kontrol eder. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) | Tüm koleksiyon öğelerini mevcut dizi öğelerine kopyalar. |
| virtual [get_Count](./get_count/)() const | Koleksiyondaki eleman sayısını alır. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Koleksiyonun yalnızca okunur olup olmadığını denetler. |
| [get_SyncRoot](./get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi alır. |
| [ICollection](./icollection/)() | Varsayılan yapıcı. |
| [ICollection](./icollection/)(const ICollection\&) | Kopya yapıcı. |
| [ICollection](./icollection/)(ICollection\&&) | Taşıma yapıcı. |
| [operator=](./operator=/)(ICollection\&&) | Taşıma atama operatörü. |
| [operator=](./operator=/)(const ICollection\&) | Taşıma atama operatörü. |
| virtual [Remove](./remove/)(const T\&) | Koleksiyondan bir öğeyi siler. |
| virtual [~ICollection](./~icollection/)() | Yıkıcı. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ThisType](./thistype/) | Koleksiyon türü adı. |
| [ValueType](./valuetype/) | RTTI bilgisi. |

## Ayrıca Bakınız

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
