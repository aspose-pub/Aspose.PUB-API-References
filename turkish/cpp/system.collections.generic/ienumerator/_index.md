---
title: "System::Collections::Generic::IEnumerator sınıfı"
linktitle: "IEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::IEnumerator sınıfı. Bazı öğeler üzerinde yineleme yapmak için kullanılabilen bir yineleyicinin arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2300
url: /tr/cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Bazı öğeler üzerinde yineleme yapmak için kullanılabilecek bir enumerator arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | VirtualizedIterator sınıfı tarafından kullanılacak yineleyiciyi hazırlar. |
| [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| virtual [Current](./current/)() const | Geçerli öğeyi alır. |
| virtual [get_Current](./get_current/)() const | Geçerli öğeyi alır. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri taşır. |
| [InitializeIterator](./initializeiterator/)() override | İlk [MoveNext()](./movenext/) çağrısını yapar ve yineleyici nesnesini VirtualizedIterator tarafından kullanılmak üzere hazırlar. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Sanallaştırılmış yineleyiciye ait yineleyiciyi işaretler. |
| virtual [MoveNext](./movenext/)() | Enumerator'ı bir sonraki öğeye taşır. Daha önce bir öğe referans alınmamışsa, referansı mevcut ilk öğeye ayarlar. Eğer konteyner sonuna gelinmişse, hiçbir şey yapmaz. |
| virtual [Reset](./reset/)() | Enumerator'ı ilk öğeden önceki konuma sıfırlar. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ValueType](./valuetype/) | Değer türü. |
## Açıklamalar



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // List sınıfı örneğini oluştur.
  auto collection = MakeObject<List<int>>();

  // Listeyi doldur.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Listenin yineleyicisini al.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Mevcut öğeyi al ve yazdır.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Yineleyiciyi sıfırla.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
