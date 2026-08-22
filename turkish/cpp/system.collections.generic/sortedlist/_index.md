---
title: "System::Collections::Generic::SortedList sınıfı"
linktitle: "SortedList"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::SortedList sınıfı. FlatMap yapısını saran sıralı liste. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 4200
url: /tr/cpp/system.collections.generic/sortedlist/
---
## SortedList class


FlatMap yapısını saran sıralı liste. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```


| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtar türü. |
| TValue | Değer türü. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [crbegin](./crbegin/)() const | Koleksiyonun son const nitelikli öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [crend](./crend/)() const | Koleksiyonun başlangıcından önceki mevcut olmayan const nitelikli öğe için bir ters yineleyici alır. |
| [get_Capacity](./get_capacity/)() const | Mevcut listenin kapasitesini alır. |
| [get_Keys](./get_keys/)() const |  |
| [get_Values](./get_values/)() const |  |
| [GetEnumerator](./getenumerator/)() override | Mevcut listeden yineleyen yineleyiciyi alır. |
| [IndexOfKey](./indexofkey/)(TKey) const | Belirli bir anahtarı arar. |
| [IndexOfValue](./indexofvalue/)(TValue) const | Belirli bir değeri arar. |
| [rbegin](./rbegin/)() | Koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [rbegin](./rbegin/)() const | Const nitelikli koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [RemoveAt](./removeat/)(int) | Belirtilen konumdaki öğeyi kaldırır. |
| [rend](./rend/)() | Koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [rend](./rend/)() const | Const nitelikli koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [set_Capacity](./set_capacity/)(int) | Mevcut listenin kapasitesini ayarlar. |
| [SortedList](./sortedlist/)() | Boş bir liste oluşturur. |
| [SortedList](./sortedlist/)(const SharedPtr\<IComparer\<TKey\>\>\&) | Boş bir liste oluşturur. |
| [SortedList](./sortedlist/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopya yapıcı. |
| [SortedList](./sortedlist/)(const map_t\&) | Kopya yapıcı. |
| [SortedList](./sortedlist/)(int) | Boş bir liste oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [const_reverse_iterator](./const_reverse_iterator/) | Sabit ters yineleyici türü. |
| [IEnumerablePtr](./ienumerableptr/) | Aynı çift tipinin koleksiyonu. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) türü. |
| [iterator](./iterator/) | Yineleyici türü. |
| [KeyCollection](./keycollection/) | Anahtar koleksiyon tipi. |
| [KVPair](./kvpair/) | Anahtar-değer çifti tipi. |
| [map_t](./map_t/) | Alt veri tipi. |
| [Ptr](./ptr/) | İşaretçi türü. |
| [reverse_iterator](./reverse_iterator/) | Ters yineleyici türü. |
| [this_t](./this_t/) | Bu tip. |
| [ValueCollection](./valuecollection/) | Değer koleksiyon tipi. |

## Ayrıca Bakınız

* Class [SortedListHelper](../sortedlisthelper/)
* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
