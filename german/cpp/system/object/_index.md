---
title: "System::Object-Klasse"
linktitle: "Objekt"
second_title: "Aspose.PUB für C++"
description: "System::Object-Klasse. Basisklasse, die die Verwendung von Methoden ermöglicht, die für die System.Object-Klasse in C# verfügbar sind. Alle nicht-trivialen Klassen, die in der übersetzten Umgebung verwendet werden, sollten sie in C++ erben."
type: docs
weight: 4800
url: /de/cpp/system/object/
---
## Object class


Basisklasse, die die Verwendung von Methoden ermöglicht, die für die [System.Object](./)-Klasse in C# verfügbar sind. Alle nicht-trivialen Klassen, die in der übersetzten Umgebung verwendet werden, sollten sie erben.

```cpp
class Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Equals](./equals/)(ptr) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](./equals/)-Semantik. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static [Equals](./equals/)(float const\&, float const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static [Equals](./equals/)(double const\&, double const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [GetCounter](./getcounter/)() | Liest die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual [GetHashCode](./gethashcode/)() const | Analog zur C# [Object.GetHashCode()](./gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [GetType](./gettype/)() const | Liest den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](./gettype/)-Aufruf. |
| virtual [Is](./is/)(const TypeInfo\&) const | Prüfen, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| [Lock](./lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| virtual [MemberwiseClone](./memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](./memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](./object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](./object/)(Object const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [operator=](./operator=/)(Object const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static [ReferenceEquals](./referenceequals/)(ptr const\&, ptr const\&) | Vergleicht Objekte nach Referenz. |
| static [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](./referenceequals/) für den Fall von string und nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, String const\&) | Spezialisierung von [Object::ReferenceEquals](./referenceequals/) für den Fall von strings. |
| [RemovedSharedRefs](./removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| [SharedCount](./sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [SharedRefAdded](./sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [ToString](./tostring/)() const | Analog zur C#-Methode [Object.ToString()](./tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static [Type](./type/)() | Implementiert das C#-Konstrukt typeof([System.Object](./)). |
| [Unlock](./unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| [WeakRefAdded](./weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [WeakRefRemoved](./weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [~Object](./~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ptr](./ptr/) | Alias für den Smart-Pointer-Typ. |
## Hinweise


Zusätzlich zu den in der C#-Klasse [System.Object](./) verfügbaren Methoden ermöglicht es auch die Unterstützung einiger Konzepte, die speziell für die übersetzte Code-Umgebung gelten. Dazu gehören Referenzzählungen, die von Smart-Pointer-Klassen verwendet werden ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) sowie weitere Dienste im Zusammenhang mit Speicherverwaltung, Debugging usw.

Jedes [Object](./) hat zwei Referenzzähler: den gemeinsamen Referenzzähler und den schwachen Referenzzähler. Der schwache Referenzzähler wird immer in einer separaten Datenstruktur gespeichert, nicht im [Object](./) selbst, was schwachen Zeigern ermöglicht, das referenzierte Objekt zu überleben. Der gemeinsame Referenzzähler wird entweder im Objekt selbst oder in derselben separaten Struktur gespeichert, abhängig vom Zustand des Makros ENABLE_EXTERNAL_REFCOUNT. Standardmäßig ist er in Debug-Builds aktiviert und in Release-Builds deaktiviert. Wenn der Smart-Pointer-Zähler im Objekt selbst gespeichert wird, wird die separate Datenstruktur nur erstellt, wenn schwache Zeiger auf das Objekt existieren. Andernfalls wird sie zusammen mit dem Objekt erstellt.

Alle Smart Pointers verwenden diese beiden Referenzzähler und tragen zur selben einzigen Eigentümergruppe bei.

Wenn eine Unterklasse von [Object](./) auf dem Stack erstellt wird, dürfen keine Smart‑Pointer darauf erstellt werden, sonst gibt es ein Problem mit der Stack‑Löschung.

Dieser Typ kann entweder im Stack als Werttyp oder im Heap mittels der Funktion [System::MakeObject()](../makeobject/) zugewiesen werden. Sobald das Objekt zugewiesen ist, dürfen diese beiden Anwendungsfälle niemals vermischt werden: Das Verwenden von [SmartPtr](../smartptr/)-Zeigern auf stack‑zugewiesene Objekte ist strikt verboten.
## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
