---
title: "Namespace System::Collections"
linktitle: "System::Collections"
second_title: "Aspose.PUB für C++"
description: "Wie man den Namespace System::Collections in C++ verwendet."
type: docs
weight: 600
url: /de/cpp/system.collections/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) von Bits, die über einen Index adressiert werden können. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BitArrayPtr](./bitarrayptr/) | Zeiger auf [BitArray](./bitarray/). Dieser Typ ist ein Zeiger, der die Löschung anderer Objekte verwaltet. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden. |
| [CollectionBase](./collectionbase/) | Stellt eine abstrakte Basisklasse für eine stark typisierte Sammlung bereit. |
| [ICollection](./icollection/) | Definiert eine nicht-generische Sammlungs-Schnittstelle. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) ist die Basisschnittstelle für alle nicht-generischen Sammlungen, die enumerierbar sind. |
| [IEnumerator](./ienumerator/) | Schnittstelle des Enumerators, der verwendet werden kann, um über einige Elemente zu iterieren. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper, der eine nicht generische [IEnumerator](./ienumerator/) Implementierung über den generischen Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) erstellt – Wrapper für die Referenztypen. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper, der eine nicht generische [IEnumerator](./ienumerator/) Implementierung über den generischen Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) erstellt – Wrapper für die Werttypen. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) stellt eine nicht generische Sammlung von Objekten dar, die einzeln über einen Index zugänglich sind. |
| [IListImplRefType](./ilistimplreftype/) | Stub, das das [System::Collections::IList](./ilist/) Interface auf einem [System::Collections::Generic::List](../system.collections.generic/list/) Objekt implementiert – Implementierung für Referenztypen. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub, das das [System::Collections::IList](./ilist/) Interface auf einem [System::Collections::Generic::List](../system.collections.generic/list/) Objekt implementiert – Implementierung für Werttypen. |
| [IListWrapper](./ilistwrapper/) | Schnittstelle zur Unterstützung des Castens von generischen zu nicht generischen Sammlungen. |
| [Invalidatable](./invalidatable/) | Klasse, die es ermöglicht, den Zustand ihrer Nachkommen über [InvalidatableTracker](./invalidatabletracker/) Objekte zu verfolgen. |
| [InvalidatableTracker](./invalidatabletracker/) | Klasse, die Tracker für [Invalidatable](./invalidatable/) Objekte implementiert. |
