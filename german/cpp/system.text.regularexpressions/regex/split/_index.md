---
title: "System::Text::RegularExpressions::Regex::Split-Methode"
linktitle: "Split"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Regex::Split-Methode. Teilt einen String anhand von Regex-Übereinstimmungen in C++."
type: docs
weight: 900
url: /de/cpp/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method


Teilt die Zeichenkette anhand von regulären Ausdrucksübereinstimmungen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) zum Aufteilen. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, int) method


Teilt die Zeichenkette anhand von regulären Ausdrucksübereinstimmungen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) zum Aufteilen. |
| Anzahl | int | Begrenzung der Anzahl von Teilstrings. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, int, int) method


Teilt einen Eingabestring bis zu einer angegebenen maximalen Anzahl von Malen in ein Array von Teilstrings, an den Positionen, die durch einen regulären Ausdruck definiert sind, welcher im [Regex](../)-Konstruktor angegeben wurde. Die Suche nach dem regulären Ausdrucksmuster beginnt an einer angegebenen Zeichenposition im Eingabestring.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Die zu teilende Zeichenkette. |
| Anzahl | int | Die maximale Anzahl, wie oft die Teilung auftreten kann. |
| startat | int | Die Zeichenposition in der Eingabezeichenkette, an der die Suche beginnt. |

### ReturnValue

Ein Array von Zeichenketten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method


Teilt die Zeichenkette anhand von Regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Muster | const String\& | Regexp-Muster. |
| count | int | Anzahlbegrenzung für [Match](../../match/). |
| Optionen | RegexOptions | Matching-Optionen. |
| matchTimeout | TimeSpan | Zeitlimit. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method


Teilt die Zeichenkette anhand von Regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Muster | const String\& | Regexp-Muster. |
| Optionen | RegexOptions | Matching-Optionen. |
| matchTimeout | TimeSpan | Zeitlimit. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
