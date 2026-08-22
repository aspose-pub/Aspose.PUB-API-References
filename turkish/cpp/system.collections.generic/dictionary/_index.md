---
title: "System::Collections::Generic::Dictionary sınıfı"
linktitle: "Sözlük"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::Dictionary sınıfı. C++'ta Dictionary sınıfının ileri bildirimi."
type: docs
weight: 1100
url: /tr/cpp/system.collections.generic/dictionary/
---
## Dictionary class


[Dictionary](./) sınıfının ileri bildirimi.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [Dictionary](./dictionary/)() | Boş bir sözlük oluşturur. |
| [Dictionary](./dictionary/)(const map_t\&) | Harita (map) üzerinden verileri kopyalar. |
| [Dictionary](./dictionary/)(int) | Önceden ayrılmış bir sözlük oluşturmayı karşılayan aşırı yükleme; aslında hiçbir tahsis yapmaz. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopya yapıcı. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Kopya yapıcı. |
| [Dictionary](./dictionary/)(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Boş bir sözlük oluşturur. |
| [Dictionary](./dictionary/)(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Boş bir sözlük oluşturur. |
| [GetEnumerator](./getenumerator/)() override | Enumerator nesnesi oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Enumerable arabirimine işaretçi. |
| [IEnumeratorPtr](./ienumeratorptr/) | Enumerator'a işaretçi. |
| [KeyCollection](./keycollection/) | RTTI bilgisi. |
| [KVPair](./kvpair/) | Anahtar-değer çifti tipi. |
| [map_t](./map_t/) | Alt veri tipi. |
| [Ptr](./ptr/) | İşaretçi türü. |
| [ValueCollection](./valuecollection/) | Çıkarılacak değerlerin koleksiyonu. |
## Açıklamalar


[Dictionary](./) that maps values to keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Dictionary sınıfı örneğini oluştur.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Sözlüğü doldur.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Sözlük öğelerini yazdır.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Ayrıca Bakınız

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
