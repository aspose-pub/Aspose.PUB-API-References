---
title: "System::Collections::ObjectModel::Collection sınıfı"
linktitle: "Collection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::ObjectModel::Collection sınıfı. Genel koleksiyon için temel tip. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 100
url: /tr/cpp/system.collections.objectmodel/collection/
---
## Collection class


Genel koleksiyon için temel tip. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Nested classes

* Class [reverse_iterator_prototype](./reverse_iterator_prototype/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const T\&) override | Değeri konteynere ekler. |
| [Clear](./clear/)() override | Tüm öğeleri siler. |
| [Collection](./collection/)() | Boş bir koleksiyon oluşturur. |
| [Collection](./collection/)(SharedPtr\<Generic::IList\<T\>\>) |  |
| [Contains](./contains/)(const T\&) const override | Öğenin koleksiyonda bulunup bulunmadığını kontrol eder. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Koleksiyon öğelerini mevcut dizi öğelerine kopyalar. |
| [crbegin](./crbegin/)() const | Koleksiyonun son const nitelikli öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [crend](./crend/)() const | Koleksiyonun başlangıcından önceki mevcut olmayan const nitelikli öğe için bir ters yineleyici alır. |
| [get_Count](./get_count/)() const override | Öğe sayısını alır. |
| [get_Items](./get_items/)() | Dahili veri yapısı erişicisi. |
| [get_Items](./get_items/)() const | Dahili veri yapısı erişicisi. |
| [GetEnumerator](./getenumerator/)() override | Koleksiyon içinde yineleme yapmak için bir enumerator alır. |
| [idx_get](./idx_get/)(int) const override | Belirtilen dizindeki değeri alır. |
| [idx_set](./idx_set/)(int, T) override | Belirtilen indeksteki değeri ayarlar. |
| [IndexOf](./indexof/)(const T\&) const override | Koleksiyonda öğeyi arar. |
| [Insert](./insert/)(int, const T\&) override | Öğeyi belirtilen konuma ekler. |
| [operator[]](./operator[]/)(int) | Belirtilen dizindeki değeri alır. |
| [operator[]](./operator[]/)(int) const | Belirtilen dizindeki değeri alır. |
| [rbegin](./rbegin/)() | Koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [rbegin](./rbegin/)() const | Const nitelikli koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [Remove](./remove/)(const T\&) override | Belirli öğeyi kaldırır. |
| [RemoveAt](./removeat/)(int) override | Belirli konumdaki öğeyi kaldırır. |
| [rend](./rend/)() | Koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [rend](./rend/)() const | Const nitelikli koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Depolanan işaretçileri zayıf hâle getirir (uygunsa). |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [const_reverse_iterator](./const_reverse_iterator/) |  |
| [reverse_iterator](./reverse_iterator/) |  |

## Ayrıca Bakınız

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PUB for C++](../../)
