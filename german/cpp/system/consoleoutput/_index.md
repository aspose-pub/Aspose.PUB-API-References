---
title: "Klasse System::ConsoleOutput"
linktitle: "ConsoleOutput"
second_title: "Aspose.PUB für C++"
description: "Klasse System::ConsoleOutput. Stellt den Standardausgabestream dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1500
url: /de/cpp/system/consoleoutput/
---
## ConsoleOutput class


Stellt den Standardausgabestream dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Encoding](./get_encoding/)() override | Gibt stets die ASCII-Kodierung zurück. |
| [Write](./write/)(bool) override | Gibt die Zeichenkettenrepräsentation des angegebenen booleschen Werts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(char_t) override | Gibt den angegebenen Zeichenwert in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(Decimal) override | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)-Werts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(double) override | Gibt die Zeichenkettenrepräsentation eines double‑Präzisions‑Gleitkommawerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(int32_t) override | Gibt die Zeichenkettenrepräsentation eines 32‑Bit‑Ganzzahlwerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(int64_t) override | Gibt die Zeichenkettenrepräsentation eines 64‑Bit‑Ganzzahlwerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(float) override | Gibt die Zeichenkettenrepräsentation eines single‑Präzisions‑Gleitkommawerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const String\&) override | Gibt das angegebene Zeichenkettenobjekt in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(uint32_t) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 32‑Bit‑Ganzzahlwerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(uint64_t) override | Gibt die Zeichenkettenrepräsentation eines vorzeichenlosen 64‑Bit‑Ganzzahlwerts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Gibt die Zeichenkettenrepräsentation eines Wertebereichs des angegebenen Zeichen-Arrays in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const char_t *) override | Gibt die angegebene C‑Zeichenkette in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const TypeInfo\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../typeinfo/)-Objekts in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [Write](./write/)(const char *) |  |
| [WriteLine](./writeline/)() override | Gibt den aktuellen Zeilenabschluss in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts, gefolgt vom aktuellen Zeilenabschluss, in den Ausgabestream aus, der vom aktuellen Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(bool) override | Gibt die Zeichenkettenrepräsentation des angegebenen bool-Werts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(char_t) override | Gibt den angegebenen Zeichenwert gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(Decimal) override | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)‑Werts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(double) override | Gibt die Zeichenkettenrepräsentation des double‑Präzisions‑Gleitkommawerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(int) override | Gibt die Zeichenkettenrepräsentation des 32‑Bit‑Ganzzahlwerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(int64_t) override | Gibt die Zeichenkettenrepräsentation des 64‑Bit‑Ganzzahlwerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(float) override | Gibt die Zeichenkettenrepräsentation des single‑Präzisions‑Gleitkommawerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const String\&) override | Gibt das angegebene Zeichenkettenobjekt gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(uint32_t) override | Gibt die Zeichenkettenrepräsentation des unsigned 32‑Bit‑Ganzzahlwerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(uint64_t) override | Gibt die Zeichenkettenrepräsentation des unsigned 64‑Bit‑Ganzzahlwerts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichenarray gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Gibt die Zeichenkettenrepräsentation eines Wertebereichs des angegebenen Zeichenarrays gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const char_t *) override | Gibt die angegebene C‑String gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const TypeInfo\&) override | Gibt die Zeichenkettenrepräsentation des angegebenen [TypeInfo](../typeinfo/)‑Objekts gefolgt vom aktuellen Zeilenabschluss an den Ausgabestream aus, der durch das aktuelle Objekt repräsentiert wird. |
| [WriteLine](./writeline/)(const char *) |  |
## Siehe auch

* Class [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
