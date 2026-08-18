---
title: "System::Text::RegularExpressions::Regex Klasse"
linktitle: "Regex"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Regex Klasse. Regulärer Ausdruck, der einer C#‑ähnlichen Syntax folgt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 800
url: /de/cpp/system.text.regularexpressions/regex/
---
## Regex class


Regulärer Ausdruck, der einer C#‑ähnlichen Syntax folgt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Regex : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Escape](./escape/)(const String\&) | Maskiert Sonderzeichen, um den String als Teil des Musters zu verwenden. |
| [get_MatchTimeout](./get_matchtimeout/)() | Gibt das Matching‑Timeout zurück. |
| [get_Options](./get_options/)() | Gibt die Regex‑Optionen zurück. |
| [get_RightToLeft](./get_righttoleft/)() | Prüft, ob das Matching im Rechts‑nach‑Links‑Modus durchgeführt wird. |
| [IsMatch](./ismatch/)(const String\&, int) | Vergleicht den Regex mit einem String. |
| static [IsMatch](./ismatch/)(const String\&, const String\&, RegexOptions, TimeSpan, int) | Prüft, ob der String dem Muster entspricht. |
| [Match](./match/)(const String\&) | Vergleicht den Regex mit einem String. |
| [Match](./match/)(const String\&, int, int) | Vergleicht den Regex mit einem String. |
| static [Match](./match/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Vergleicht String und Muster. |
| [Matches](./matches/)(const String\&, int) | Gibt alle Treffer des Regex im angegebenen String zurück, indem wiederholt gematcht wird. |
| static [Matches](./matches/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Gibt alle Treffer zwischen String und Muster zurück. |
| [Regex](./regex/)() | Erstellt einen leeren regulären Ausdruck. |
| [Regex](./regex/)(const String\&) | Konstruktor. |
| [Regex](./regex/)(const String\&, RegexOptions) | Konstruktor. |
| [Regex](./regex/)(const String\&, RegexOptions, TimeSpan) | Konstruktor. |
| [Replace](./replace/)(const String\&, const String\&) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette. |
| [Replace](./replace/)(const String\&, const char_t *) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette. |
| static [Replace](./replace/)(const String\&, const char_t *, const char_t *) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette. |
| static [Replace](./replace/)(const String\&, const String\&, const char_t *) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&) | Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int) | Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int, int) | Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) | Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten (statische Funktion). |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, RegexOptions) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette. |
| [Replace](./replace/)(const String\&, const String\&, int) | Ersetzt Teilzeichenketten in einer Zeichenkette. Nicht implementiert. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Ersetzt Teilzeichenketten in einer Zeichenkette. Nicht implementiert. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&) | Ersetzt reguläre Ausdrucksübereinstimmungen. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&) | Ersetzt reguläre Ausdrucksübereinstimmungen. |
| [Split](./split/)(const String\&) | Teilt die Zeichenkette anhand von regulären Ausdrucksübereinstimmungen. |
| [Split](./split/)(const String\&, int) | Teilt die Zeichenkette anhand von regulären Ausdrucksübereinstimmungen. |
| [Split](./split/)(const String\&, int, int) | Teilt eine Eingabezeichenkette bis zu einer angegebenen maximalen Anzahl von Malen in ein Array von Teilzeichenketten, an den Positionen, die durch einen regulären Ausdruck definiert sind, der im [Regex](./)-Konstruktor angegeben ist. Die Suche nach dem Muster des regulären Ausdrucks beginnt an einer angegebenen Zeichenposition in der Eingabezeichenkette. |
| static [Split](./split/)(const String\&, const String\&, RegexOptions, TimeSpan) | Teilt die Zeichenkette anhand von Regexp. |
| static [Split](./split/)(const String\&, const String\&, int, RegexOptions, TimeSpan) | Teilt die Zeichenkette anhand von Regexp. |
| [ToString](./tostring/)() const override | Konvertiert regulären Ausdruck in eine Zeichenkette. |
| static [Unescape](./unescape/)(const String\&) | Entschärft Sonderzeichen in einer Zeichenkette, die als Teil des Musters verwendet werden. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Spezieller Timeout-Wert, um das Abbrechen von Übereinstimmungen durch Timeout zu deaktivieren. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
