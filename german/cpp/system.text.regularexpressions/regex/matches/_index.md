---
title: "System::Text::RegularExpressions::Regex::Matches-Methode"
linktitle: "Übereinstimmungen"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Regex::Matches-Methode. Gibt alle Übereinstimmungen des Regex in einem angegebenen String zurück, indem wiederholt gematcht wird in C++."
type: docs
weight: 700
url: /de/cpp/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Gibt alle Treffer des Regex im angegebenen String zurück, indem wiederholt gematcht wird.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| startat | int | Index, bei dem das Matching beginnt. |

### ReturnValue

Sammlung aller gefundenen Übereinstimmungen.

## Siehe auch

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Gibt alle Treffer zwischen String und Muster zurück.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
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

Alle durch wiederholtes Matching gefundenen Übereinstimmungen.

## Siehe auch

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
