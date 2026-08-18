---
title: "System::Text::RegularExpressions::Regex::Match-Methode"
linktitle: "Match"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Regex::Match-Methode. Führt einen Regex-Vergleich gegen eine Zeichenkette in C++ aus."
type: docs
weight: 600
url: /de/cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Vergleicht den Regex mit einem String.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Zielzeichenkette. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Siehe auch

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Match(const String\&, int, int) method


Vergleicht den Regex mit einem String.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Zielzeichenkette. |
| startat | int | Startindex. |
| length | int | Anzahl der zu durchsuchenden Zeichen (0, um die gesamte Zeichenkette zu durchsuchen). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Siehe auch

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Vergleicht String und Muster.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Muster | const String\& | Regexp-Muster. |
| Optionen | RegexOptions | Matching-Optionen. |
| matchTimeout | TimeSpan | Zeitlimit. |
| startat | int | [Match](../../match/) Anfangsposition. |
| length | int | Anzahl der zu durchsuchenden Zeichen (0 deaktiviert die Begrenzung). |

### ReturnValue

Erster gefundener Treffer.

## Siehe auch

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
