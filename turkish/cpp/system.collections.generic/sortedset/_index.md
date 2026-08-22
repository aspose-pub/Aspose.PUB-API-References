---
title: "System::Collections::Generic::SortedSet sınıfı"
linktitle: "SortedSet"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::SortedSet sınıfı. C++'ta SortedSet sınıfının ileri bildirimi."
type: docs
weight: 4400
url: /tr/cpp/system.collections.generic/sortedset/
---
## SortedSet class


[SortedSet](./) sınıfının ileri bildirimi.

```cpp
template<typename T>class SortedSet : public System::Collections::Generic::BaseSet<T, std::set<T, ComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [SortedSet](./sortedset/)() | RTTI bilgisi. |
| [SortedSet](./sortedset/)(int) | Belirtilen kapasiteyle boş bir küme oluşturur. |
| [SortedSet](./sortedset/)(const SharedPtr\<IComparer\<T\>\>\&) | Belirtilen eşitlik karşılaştırıcısını kullanan boş bir küme oluşturur. |
| [SortedSet](./sortedset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Enumerable değerlerine dayalı [SortedSet](./) oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Vase türü. |
| [ThisPtr](./thisptr/) | İşaretçi türü. |
| [ThisType](./thistype/) | Kendisi tipi. |
## Açıklamalar


Siparişli nesneler kümesinin uygulanması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına (stack) veya new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçmek için kullanın.

## Ayrıca Bakınız

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
