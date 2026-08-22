---
title: "System::Collections::IListImplValueType sınıfı"
linktitle: "IListImplValueType"
second_title: "Aspose.PUB için C++"
description: "System::Collections::IListImplValueType sınıfı. System::Collections::Generic::List nesnesi üzerinde System::Collections::IList arayüzünü uygulayan bir stub - C++'ta değer tipleri için uygulama."
type: docs
weight: 1200
url: /tr/cpp/system.collections/ilistimplvaluetype/
---
## IListImplValueType class


Bir stub, [System::Collections::IList](../ilist/) arayüzünü [System::Collections::Generic::List](../../system.collections.generic/list/) nesnesi üzerinde uygular - değer tipleri için uygulama.

```cpp
template<typename T>class IListImplValueType : public virtual System::Collections::IList
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Elemanı listenin sonuna ekler. |
| [Clear](./clear/)() override | Tüm öğeleri siler. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Öğenin listede bulunup bulunmadığını kontrol eder. |
| [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) yöntemlerinin uygulaması koleksiyondaki öğe sayısını alır. |
| [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) uygulaması bir koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [idx_get](./idx_get/)(int, int) const override | Belirtilen indeksdeki öğeyi alır. |
| [IListImplValueType](./ilistimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IList\<T\>\>) | Yeni nesne örneği oluşturur. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Öğenin kapsayıcıda ilk ortaya çıkışının dizinini alır. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Elemanı belirtilen konuma ekler, diğer elemanları kaydırır. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Belirli öğenin listeden ilk örneğini kaldırır. |
| [RemoveAt](./removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |
## Ayrıca Bakınız

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
