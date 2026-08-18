---
title: "System::Collections::IEnumeratorImplRefType Klasse"
linktitle: "IEnumeratorImplRefType"
second_title: "Aspose.PUB für C++"
description: "System::Collections::IEnumeratorImplRefType Klasse. Wrapper, der eine nicht-generische IEnumerator-Implementierung über den generischen Iterator IEnumeratorImplRefType erstellt – Wrapper für Referenztypen in C++."
type: docs
weight: 700
url: /de/cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Wrapper, der eine nicht-generische [IEnumerator](../ienumerator/) Implementierung über den generischen Iterator [IEnumeratorImplRefType](./) erstellt – Wrapper für Referenztypen.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Current](./get_current/)() const override | Liefert das aktuelle Element. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | Wrapper-Konstruktor |
| [MoveNext](./movenext/)() override | Bewegt den Enumerator zum nächsten Element. Wenn zuvor kein Element referenziert wurde, wird die Referenz auf das erste verfügbare Element gesetzt. Wenn das Ende des Containers erreicht wurde, passiert nichts. |

## Siehe auch

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
