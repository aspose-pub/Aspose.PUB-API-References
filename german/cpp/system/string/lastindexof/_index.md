---
title: "System::String::LastIndexOf Methode"
linktitle: "LastIndexOf"
second_title: "Aspose.PUB für C++"
description: "System::String::LastIndexOf Methode. Rückwärtsnachschlagen eines Zeichens in C++."
type: docs
weight: 2300
url: /de/cpp/system/string/lastindexof/
---
## String::LastIndexOf(char_t) const method


Zeichen-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(char_t value) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char_t | Zeichen, nach dem gesucht wird. |

### ReturnValue

Index der letzten Zeichenposition oder -1, falls nicht gefunden.

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(char_t, int32_t) const method


Zeichen-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int32_t | Index, ab dem die Suche gestartet wird. |

### ReturnValue

Index der letzten Zeichenposition seit startIndex oder -1, falls nicht gefunden.

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(char_t, int32_t, int32_t) const method


Zeichen-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int32_t | Index, ab dem die Suche gestartet wird. |
| Anzahl | int32_t | Anzahl der zu durchsuchenden Zeichen |

### ReturnValue

Index der letzten Zeichenposition seit startIndex oder -1, falls nicht gefunden.

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(const String\&, int, System::StringComparison) const method


Substring-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) Modus. |

### ReturnValue

Index des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## Siehe auch

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(const String\&, int) const method


Substring-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |

### ReturnValue

Index des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(const String\&, System::StringComparison) const method


Substring-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | Zu suchender Teilstring. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) Modus. |

### ReturnValue

Index des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer die Stringlänge zurückgegeben.

## Siehe auch

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOf(const String\&, int, int, StringComparison) const method


Substring-Rückwärtssuche.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const String\& | Zu suchender Teilstring. |
| startIndex | int | Position im Quellstring, ab der die Suche gestartet wird. |
| Anzahl | int | Anzahl der zu durchsuchenden Zeichen. |
| comparisonType | StringComparison | [Comparison](../../comparison/) Modus. |

### ReturnValue

Index des zuletzt gefundenen Teilstrings oder -1, wenn nicht gefunden. Für einen leeren Suchstring wird immer startIndex+count zurückgegeben.

## Siehe auch

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
