---
title: "System::String::IndexOfAny Methode"
linktitle: "IndexOfAny"
second_title: "Aspose.PUB für C++"
description: "System::String::IndexOfAny Methode. Vorwärtsnachschlagen von Zeichen in C++."
type: docs
weight: 1500
url: /de/cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Zeichen-Vorwärtssuche.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int | Index, ab dem die Suche gestartet wird. |

### ReturnValue

Index der ersten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Sucht nach beliebigen der übergebenen Zeichen im gesamten String. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite Zeichen usw. Gibt den Index des ersten Zeichens zurück, das eines der Zielzeichen enthält.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |

### ReturnValue

Index des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Sucht nach beliebigen der übergebenen Zeichen im Substring. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite Zeichen usw. Gibt den Index des ersten Zeichens zurück, das eines der Zielzeichen enthält.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |
| startindex | int32_t | Index, ab dem die Suche gestartet wird. |

### ReturnValue

Index des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Sucht nach beliebigen der übergebenen Zeichen im Substring. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite Zeichen usw. Gibt den Index des ersten Zeichens zurück, das eines der Zielzeichen enthält.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |
| startindex | int32_t | Index, ab dem die Suche gestartet wird. |
| Anzahl | int32_t | Anzahl der zu durchsuchenden Zeichen. |

### ReturnValue

Index des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const String\&, int) const method


Sucht folglich nach allen Zeichen von str in diesem. Wird das erste Zeichen gefunden, wird seine Position zurückgegeben, andernfalls wird das zweite Zeichen und so weiter gesucht.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | [String](../) von zu suchenden Zeichen. Die Reihenfolge der Zeichen ist wichtig. |
| startIndex | int | Position, ab der die Suche gestartet wird. |

### ReturnValue

Index des zuerst gefundenen Zeichens oder -1, wenn keines gefunden wird.

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
