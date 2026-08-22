---
title: "System::Collections::ObjectModel::ReadOnlyCollection sınıfı"
linktitle: "ReadOnlyCollection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::ObjectModel::ReadOnlyCollection sınıfı. Belirli bir konteyneri yalnızca okuma kipinde erişmek için sarar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 300
url: /tr/cpp/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection class


Belirli bir konteyneri yalnızca okuma kipinde erişmek için sarar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) ya da operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Contains](./contains/)(const T\&) const override | Konteynerin belirli bir öğeyi içerip içermediğini denetler. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Konteyner öğelerini mevcut dizi öğelerine kopyalar. |
| [get_Count](./get_count/)() const override | Konteyner öğelerinin sayısını alır. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Koleksiyonun yalnızca okunur olup olmadığını denetler. |
| [GetEnumerator](./getenumerator/)() override | Koleksiyon yineleyicisini alır. |
| [idx_get](./idx_get/)(int) const override | Belirli konumdaki öğeyi alır. |
| [IndexOf](./indexof/)(const T\&) const override | Koleksiyonda belirli bir öğeyi arar. |
| [ReadOnlyCollection](./readonlycollection/)(const SharedPtr\<Generic::IList\<T\>\>\&) | Belirli bir koleksiyonun etrafına yalnızca okunur bir koleksiyon sarar. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Yalnızca veri saran ve hiçbir şey depolamayan salt okunur bir koleksiyon olduğu için hiçbir şey yapmaz. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) | Uygulanan arayüz. |
| [IEnumeratorPtr](./ienumeratorptr/) | Aynı öğelerden oluşan kapsayıcı. |
| [ValueType](./valuetype/) | Değer türü. |

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PUB for C++](../../)
