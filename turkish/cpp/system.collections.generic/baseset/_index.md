---
title: "System::Collections::Generic::BaseSet sınıfı"
linktitle: "BaseSet"
second_title: "Aspose.PUB için C++"
description: "C++'de System::Collections::Generic::BaseSet sınıfını nasıl kullanılır?"
type: docs
weight: 800
url: /tr/cpp/system.collections.generic/baseset/
---
## BaseSet class




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++'a özgü. |
| [Add](./add/)(const T\&) override | Kümeye öğe ekler. |
| [begin](./begin/)() const | Const nitelikli koleksiyonun ilk öğesine bir yineleyici alır. |
| [cbegin](./cbegin/)() const | Koleksiyonun ilk const nitelikli öğesine bir yineleyici alır. |
| [cend](./cend/)() const | Koleksiyonun sonundan sonraki mevcut olmayan const nitelikli bir öğe için bir yineleyici alır. |
| [Clear](./clear/)() override | Kümedeki tüm öğeleri siler. |
| [Contains](./contains/)(const T\&) const override | Öğenin kümede bulunup bulunmadığını kontrol eder. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Hash içeriğini mevcut dizi öğelerine kopyalar. |
| [data](./data/)() | Alt veri yapısı erişicisi. |
| [data](./data/)() const | Alt veri yapısı erişicisi. |
| [end](./end/)() const | Const nitelikli koleksiyonun sonundan sonraki mevcut olmayan bir öğe için bir yineleyici alır. |
| [get_Count](./get_count/)() const override | Kümedeki öğe sayısını alır. |
| [GetEnumerator](./getenumerator/)() override | Enumeratörü oluşturur. |
| [Remove](./remove/)(const T\&) override | Kümeden öğeyi kaldırır. |
| [TryAdd](./tryadd/)(const T\&) | Kümeye öğe ekler. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Uygulanan arayüz. |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [IEnumerablePtr](./ienumerableptr/) | Yinelemeli arayüz işaretçisi. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) işaretçisi. |
| [iterator](./iterator/) | Yineleyici türü. |
| [set_t](./set_t/) | Alt veri tipi. |
| [ThisPtr](./thisptr/) | İşaretçi türü. |
| [ThisType](./thistype/) | Kendisi tipi. |
| [ValueType](./valuetype/) | Değer türü. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
