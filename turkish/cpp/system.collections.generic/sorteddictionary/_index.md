---
title: "System::Collections::Generic::SortedDictionary sınıfı"
linktitle: "SortedDictionary"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::SortedDictionary sınıfı. C++'ta sıralı sözlük tipi ileri bildirim."
type: docs
weight: 4000
url: /tr/cpp/system.collections.generic/sorteddictionary/
---
## SortedDictionary class


Sıralı sözlük tipi ileri bildirimi.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [get_Comparer](./get_comparer/)() const | SortedDictionary<TKey,TValue> öğelerinin sırasını belirlemek için kullanılan IComparer<TKey>'ı alır. |
| static [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Tekil örnek erişim işlevi. |
| [GetEnumerator](./getenumerator/)() override | Mevcut sözlüğü yinelemek için yineleyici alır. |
| [rbegin](./rbegin/)() | Koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [rbegin](./rbegin/)() const | Const nitelikli koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [rend](./rend/)() | Koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [rend](./rend/)() const | Const nitelikli koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [SortedDictionary](./sorteddictionary/)() | Boş sözlük oluşturur. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Boş sözlük oluşturur. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopya yapıcı. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Kopya yapıcı. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [const_reverse_iterator](./const_reverse_iterator/) | Sabit ters yineleyici türü. |
| [IEnumerablePtr](./ienumerableptr/) | Aynı öğelerden oluşan koleksiyon. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) türü. |
| [iterator](./iterator/) | Yineleyici türü. |
| [KeyCollection](./keycollection/) | Anahtar koleksiyon tipi. |
| [KVPair](./kvpair/) | Anahtar-değer çifti tipi. |
| [map_t](./map_t/) | Alt veri tipi. |
| [Ptr](./ptr/) | İşaretçi türü. |
| [reverse_iterator](./reverse_iterator/) | Ters yineleyici türü. |
| [this_t](./this_t/) | Kendisi tipi. |
| [ValueCollection](./valuecollection/) | Değer koleksiyon tipi. |
## Açıklamalar


STL haritasını saran sıralı sözlük sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
