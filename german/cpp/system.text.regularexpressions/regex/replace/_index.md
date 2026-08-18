---
title: "System::Text::RegularExpressions::Regex::Replace-Methode"
linktitle: "Ersetzen"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Regex::Replace-Methode. Ersetzt alle Regex-Treffer in einer Zeichenkette durch die Ersatzzeichenkette in C++."
type: docs
weight: 800
url: /de/cpp/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const char_t *) method


Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Ersatz | const char_t * | Ersatzzeichenkette. |

### ReturnValue

Eingabezeichenkette, bei der alle Regex-Treffer durch die Ersatzzeichenkette ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&) method


Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Auswerter | const MatchEvaluator\& | Delegat zur Erzeugung von Ersatzzeichenketten basierend auf Treffern. |

### ReturnValue

Eingabezeichenketten, bei denen alle Treffer ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int) method


Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Auswerter | const MatchEvaluator\& | Delegat zur Erzeugung von Ersatzzeichenketten basierend auf Treffern. |
| Anzahl | int | Begrenzung der Anzahl von Ersetzungen. |

### ReturnValue

Eingabezeichenketten, bei denen alle Treffer ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method


Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Auswerter | const MatchEvaluator\& | Delegat zur Erzeugung von Ersatzzeichenketten basierend auf Treffern. |
| Anzahl | int | Begrenzung der Anzahl von Ersetzungen. |
| startat | int | Index in der Eingabezeichenkette, an dem die Ersetzung beginnen soll. |

### ReturnValue

Eingabezeichenketten, bei denen alle Treffer ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&) method


Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Ersatz | const String\& | Ersatzzeichenkette. |

### ReturnValue

Eingabezeichenkette, bei der alle Regex-Treffer durch die Ersatzzeichenkette ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, int) method


Ersetzt Teilzeichenketten in einer Zeichenkette. Nicht implementiert.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, int, int) method


Ersetzt Teilzeichenketten in einer Zeichenkette. Nicht implementiert.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const char_t *, const char_t *) method


Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| pattern | const char_t * | Muster für [Regex](../). |
| Ersatz | const char_t * | Ersatzzeichenkette. |

### ReturnValue

Eingabezeichenkette, bei der alle Regex-Treffer durch die Ersatzzeichenkette ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, const char_t *) method


Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| pattern | const String\& | Muster für [Regex](../). |
| Ersatz | const char_t * | Ersatzzeichenkette. |

### ReturnValue

Eingabezeichenkette, bei der alle Regex-Treffer durch die Ersatzzeichenkette ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method


Ersetzt reguläre Ausdrucksübereinstimmungen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Muster | const String\& | Regexp-Muster. |
| Auswerter | const MatchEvaluator\& | Delegat zur Erzeugung einer Ersatzzeichenkette für jeden Treffer. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method


Ersetzt alle Übereinstimmungen in einer Zeichenkette durch vom Delegaten erzeugte Ersetzungszeichenketten (statische Funktion).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| pattern | const String\& | Muster für [Regex](../). |
| Auswerter | const MatchEvaluator\& | Delegat zur Erzeugung von Ersatzzeichenketten basierend auf Treffern. |
| options | RegexOptions | [Regex](../) Optionen. |

### ReturnValue

Eingabezeichenketten, bei denen alle Treffer ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&) method


Ersetzt reguläre Ausdrucksübereinstimmungen.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| Muster | const String\& | Regexp-Muster. |
| Ersatz | const String\& | Ersatzzeichenkette. |

### ReturnValue

[String](../../../system/string/) with all matches replaced.

## Siehe auch

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method


Ersetzt alle Übereinstimmungen des regulären Ausdrucks in einer Zeichenkette durch die Ersetzungszeichenkette.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | const String\& | Eingabezeichenkette. |
| pattern | const String\& | Muster für [Regex](../). |
| Ersatz | const String\& | Ersatzzeichenkette. |
| options | RegexOptions | [Regex](../) Optionen. |

### ReturnValue

Eingabezeichenkette, bei der alle Regex-Treffer durch die Ersatzzeichenkette ersetzt wurden.

## Siehe auch

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
