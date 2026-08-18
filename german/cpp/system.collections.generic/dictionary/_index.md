---
title: "System::Collections::Generic::Dictionary Klasse"
linktitle: "Dictionary"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::Dictionary Klasse. Vorwärtsdeklaration der Dictionary-Klasse in C++."
type: docs
weight: 1100
url: /de/cpp/system.collections.generic/dictionary/
---
## Dictionary class


Vorwärtsdeklaration der [Dictionary](./) Klasse.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```


| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Dictionary](./dictionary/)() | Erstellt ein leeres Dictionary. |
| [Dictionary](./dictionary/)(const map_t\&) | Kopiert Daten aus der Map. |
| [Dictionary](./dictionary/)(int) | Überladung, die dem Erzeugen eines vorab zugewiesenen Dictionary entspricht; führt tatsächlich keine Allokation durch. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopierkonstruktor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Kopierkonstruktor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Erstellt ein leeres Dictionary. |
| [Dictionary](./dictionary/)(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Erstellt ein leeres Dictionary. |
| [GetEnumerator](./getenumerator/)() override | Erstellt ein Enumerator‑Objekt. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Zeiger auf das aufzählbare Interface. |
| [IEnumeratorPtr](./ienumeratorptr/) | Zeiger auf den Enumerator. |
| [KeyCollection](./keycollection/) | RTTI-Informationen. |
| [KVPair](./kvpair/) | Schlüssel‑Wert‑Paar‑Typ. |
| [map_t](./map_t/) | Zugrundeliegender Datentyp. |
| [Ptr](./ptr/) | Zeigertyp. |
| [ValueCollection](./valuecollection/) | Sammlung von zu extrahierenden Werten. |
## Hinweise


[Dictionary](./) that maps values to keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Erstellen Sie die Instanz der Dictionary-Klasse.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Füllen Sie das Wörterbuch.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Geben Sie die Elemente des Wörterbuchs aus.
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

## Siehe auch

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
