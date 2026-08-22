---
title: "System::Collections::Generic::LinkedList sınıfı"
linktitle: "LinkedList"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::LinkedList sınıfı. C++'ta LinkedList ileri bildirimidir."
type: docs
weight: 3100
url: /tr/cpp/system.collections.generic/linkedlist/
---
## LinkedList class


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


| Parametre | Açıklama |
| --- | --- |
| T | İçerilen değer türü. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const T\&) override | Liste sonuna **element** ekler. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Listenin **node** öğesinden sonra **element** ekler. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Listenin **node** öğesinden sonra **newNode** ekler. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Listenin **node** öğesinden önce **element** ekler. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Listenin **node** öğesinden önce **newNode** ekler. |
| [AddFirst](./addfirst/)(const T\&) | Listenin başına **element** ekler. |
| [AddFirst](./addfirst/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Listenin başına **newNode** ekler. |
| [AddLast](./addlast/)(const T\&) | Liste sonuna **element** ekler. |
| [AddLast](./addlast/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Listenin sonuna **newNode** ekler. |
| [begin](./begin/)() | Koleksiyonun ilk öğesine bir yineleyici alır. |
| [begin](./begin/)() const | Const nitelikli koleksiyonun ilk öğesine bir yineleyici alır. |
| [cbegin](./cbegin/)() const | Koleksiyonun ilk const nitelikli öğesine bir yineleyici alır. |
| [cend](./cend/)() const | Koleksiyonun sonundan sonraki mevcut olmayan const nitelikli bir öğe için bir yineleyici alır. |
| [Clear](./clear/)() override | Listedeki tüm öğeleri siler. |
| [Contains](./contains/)(const T\&) const override | Listenin içinde **element** olup olmadığını kontrol eder. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Kapsayıcı verilerini mevcut dizi öğelerine kopyalar. |
| [crbegin](./crbegin/)() const | Koleksiyonun son const nitelikli öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [crend](./crend/)() const | Koleksiyonun başlangıcından önceki mevcut olmayan const nitelikli öğe için bir ters yineleyici alır. |
| [end](./end/)() | Koleksiyonun sonundan sonraki mevcut olmayan bir öğe için bir yineleyici alır. |
| [end](./end/)() const | Const nitelikli koleksiyonun sonundan sonraki mevcut olmayan bir öğe için bir yineleyici alır. |
| [Find](./find/)(const T\&) const | Listedeki bir **element** için ileri yönde arama yapar. |
| [FindLast](./findlast/)(const T\&) const | Listedeki bir **element** için ters yönde arama yapar. |
| [get_Count](./get_count/)() const override | Listedeki öğe sayısını alır. |
| [get_First](./get_first/)() const | Listedeki ilk öğeye işaretçiyi alır. |
| [get_Last](./get_last/)() const | Listedeki son öğeye işaretçiyi alır. |
| [GetEnumerator](./getenumerator/)() override | Mevcut [LinkedList](./) üzerinden yineleme yapmak için bir enumerator alır. |
| [LinkedList](./linkedlist/)() | Boş bir [LinkedList](./) oluşturur. |
| [LinkedList](./linkedlist/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Kopya yapıcı. |
| [rbegin](./rbegin/)() | Koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [rbegin](./rbegin/)() const | Const nitelikli koleksiyonun son öğesine (ters yönde ilk) bir ters yineleyici alır. |
| [Remove](./remove/)(const T\&) override | Listeden belirtilen **element**'in ilk oluşumunu kaldırır. |
| [Remove](./remove/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Listeden düğümü kaldırır. |
| [RemoveFirst](./removefirst/)() | Listeden ilk düğümü kaldırır. |
| [RemoveLast](./removelast/)() | Listeden son düğümü kaldırır. |
| [rend](./rend/)() | Koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [rend](./rend/)() const | Const nitelikli koleksiyonun başlangıcından önceki mevcut olmayan öğe için bir ters yineleyici alır. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [const_iterator](./const_iterator/) | Sabit yineleyici türü. |
| [const_reverse_iterator](./const_reverse_iterator/) | Sabit ters yineleyici türü. |
| [iterator](./iterator/) | Yineleyici türü. |
| [list_t](./list_t/) | Alt veri tipi. |
| [reverse_iterator](./reverse_iterator/) | Ters yineleyici türü. |
## Açıklamalar


Bağlantılı liste kapsayıcısı. std::list üzerine bir sarmalayıcı uygular. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçmek için kullanın.


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // LinkedList sınıfının bir örneğini oluştur.
  auto list = MakeObject<LinkedList<int>>();

  // Bağlı listeyi doldurun.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // Bağlı listedeki öğeleri yazdırın.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
1 15 25 30
*/
```

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Class [Invalidatable](../../system.collections/invalidatable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
