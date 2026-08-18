---
title: "System::Globalization::StringInfo Klasse"
linktitle: "StringInfo"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::StringInfo Klasse. Aufteiler zum Durchlaufen von Zeichenkettenabschnitten. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2400
url: /de/cpp/system.globalization/stringinfo/
---
## StringInfo class


Aufteiler zum Durchlaufen von Zeichenkettenabschnitten. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class StringInfo : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LengthInTextElements](./get_lengthintextelements/)() const | Ermittelt die Anzahl der Textelemente im [StringInfo](./)-Objekt. |
| [get_String](./get_string/)() const | Ermittelt den Wert des [StringInfo](./)-Objekts. |
| [GetHashCode](./gethashcode/)() const override | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&) | Ermittelt das erste Element in der angegebenen Zeichenkette. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&, int) | Ermittelt das Element am angegebenen Index der angegebenen Zeichenkette. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&) | Erstellt einen Enumerator zum Durchlaufen der Zeichen einer Zeichenkette. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&, int) | Erstellt einen Enumerator zum Durchlaufen der Zeichen einer Zeichenkette, beginnend beim angegebenen Index. |
| [operator=](./operator=/)(const StringInfo\&) |  |
| static [ParseCombiningCharacters](./parsecombiningcharacters/)(const String\&) | Ermittelt die Indizes der Basiszeichen, High Surrogates und Steuerzeichen. |
| [set_String](./set_string/)(const String\&) | Setzt den Wert des [StringInfo](./)-Objekts. |
| [StringInfo](./stringinfo/)() | RTTI-Informationen. |
| [StringInfo](./stringinfo/)(const String\&) | Konstruktor. |
| [StringInfo](./stringinfo/)(const StringInfo\&) |  |
| [SubstringByTextElements](./substringbytextelements/)(int) const | Ermittelt die Teilzeichenkette von Textelementen vom angegebenen Textelement bis zum letzten Textelement. |
| [SubstringByTextElements](./substringbytextelements/)(int, int) const | Ermittelt die Teilzeichenkette von Textelementen vom angegebenen Textelement über die angegebene Anzahl von Textelementen. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
