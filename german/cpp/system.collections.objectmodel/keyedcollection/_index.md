---
title: "System::Collections::ObjectModel::KeyedCollection Klasse"
linktitle: "KeyedCollection"
second_title: "Aspose.PUB für C++"
description: "System::Collections::ObjectModel::KeyedCollection Klasse. Abstrakte Sammlung von Elementen mit eingebetteten Schlüsseln. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.collections.objectmodel/keyedcollection/
---
## KeyedCollection class


Abstrakte Sammlung von Elementen mit eingebetteten Schlüsseln. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename TKey,typename TItem>class KeyedCollection : public System::Collections::ObjectModel::Collection<TItem>
```


| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TItem | Werttyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Add](./add/)(const TItem\&) override | Fügt ein Element am Ende des Containers hinzu. |
| [Contains](./contains/)(TKey) | Prüft, ob der Schlüssel im Container vorhanden ist. |
| [get_Comparer](./get_comparer/)() | Liest den Comparer. |
| [idx_get](./idx_get/)(TKey) | Liest das Element an einem bestimmten Index. |
| [Remove](./remove/)(TKey) | Entfernt den Schlüssel aus dem Container. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Bewirkt, dass ein bestimmtes Template-Argument als schwacher Zeiger statt als Shared‑Pointer behandelt wird (falls zutreffend). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [defaultThreshold](./defaultthreshold/) | Schwellenwert für die Erstellung des Lookup‑Wörterbuchs, Standard. |

## Siehe auch

* Class [Collection](../collection/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PUB for C++](../../)
