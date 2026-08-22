---
title: "System::Collections::Generic::HashSet sınıfı"
linktitle: "HashSet"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::HashSet sınıfı. C++'ta HashSet sınıfının ileri bildirimidir."
type: docs
weight: 1700
url: /tr/cpp/system.collections.generic/hashset/
---
## HashSet class


[HashSet](./) sınıfının ileri bildirimi.

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [HashSet](./hashset/)() | RTTI bilgisi. |
| [HashSet](./hashset/)(int) | Belirtilen kapasiteyle boş bir küme oluşturur. |
| [HashSet](./hashset/)(const SharedPtr\<IEqualityComparer\<T\>\>\&) | Belirtilen eşitlik karşılaştırıcısını kullanan boş bir küme oluşturur. |
| [HashSet](./hashset/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Yinelemeli değerlere dayalı bir hashset oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Temel tip. |
| [ThisPtr](./thisptr/) | İşaretçi türü. |
| [ThisType](./thistype/) | Kendisi tipi. |
## Açıklamalar


Kümeyi hashleme temelli olarak uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

## Ayrıca Bakınız

* Class [BaseSet](../baseset/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
