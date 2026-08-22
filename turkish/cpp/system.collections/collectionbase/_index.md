---
title: "System::Collections::CollectionBase sınıfı"
linktitle: "CollectionBase"
second_title: "Aspose.PUB için C++"
description: "System::Collections::CollectionBase sınıfı. C++'ta güçlü tiplenmiş bir koleksiyon için soyut bir temel sınıf sağlar."
type: docs
weight: 300
url: /tr/cpp/system.collections/collectionbase/
---
## CollectionBase class


Güçlü tiplenmiş bir koleksiyon için soyut bir temel sınıf sağlar.

```cpp
template<typename T>class CollectionBase : public virtual System::Collections::Generic::IEnumerable<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyonun öğelerinin türü |
## Nested classes

* Class [ListImpl](./listimpl/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clear](./clear/)() | Koleksiyon örneğindeki tüm nesneleri kaldırır. Bu yöntem geçersiz kılınamaz. |
| [get_Capacity](./get_capacity/)() | Koleksiyonun içerebileceği öğe sayısını döndürür. |
| [get_Count](./get_count/)() | Koleksiyon örneğinde bulunan öğe sayısını döndürür. Bu yöntem geçersiz kılınamaz. |
| [GetEnumerator](./getenumerator/)() override | Koleksiyon örneği üzerinde yineleme yapan bir enumerator döndürür. |
| [RemoveAt](./removeat/)(int32_t) | Koleksiyon örneğinin belirtilen indeksindeki öğeyi kaldırır. Bu yöntem geçersiz kılınamaz. |
| [set_Capacity](./set_capacity/)(int32_t) | Koleksiyonun içerebileceği öğe sayısını ayarlar. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) olarak ayarlayın. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |

## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
