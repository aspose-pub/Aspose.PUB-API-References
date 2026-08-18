---
title: "System::String::LastIndexOfAny-Methode"
linktitle: "LastIndexOfAny"
second_title: "Aspose.PUB für C++"
description: "System::String::LastIndexOfAny-Methode. Durchsucht den gesamten String rückwärts nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen des Strings mit allen Zeichen in anyOf, dann das vorherige und so weiter. Gibt den Index der ersten gefundenen Übereinstimmung in C++ zurück."
type: docs
weight: 2400
url: /de/cpp/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Sucht nach beliebigen der übergebenen Zeichen im gesamten String rückwärts. Vergleicht das letzte Zeichen des Strings mit allen Zeichen in anyOf, dann das vorherige Zeichen usw. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |

### ReturnValue

Index des letzten passenden Zeichens oder -1, falls nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Sucht nach beliebigen der übergebenen Zeichen im Substring rückwärts. Vergleicht das letzte Zeichen des Strings mit allen Zeichen in anyOf, dann das vorherige Zeichen usw. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |
| startindex | int32_t | Index, ab dem die Suche gestartet wird. |

### ReturnValue

Index des letzten passenden Zeichens oder -1, falls nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Sucht nach beliebigen der übergebenen Zeichen im Substring rückwärts. Vergleicht das letzte Zeichen des Strings mit allen Zeichen in anyOf, dann das vorherige Zeichen usw. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist egal. |
| startindex | int32_t | Index, ab dem die Suche gestartet wird. |
| Anzahl | int32_t | Anzahl der zu durchsuchenden Zeichen. |

### ReturnValue

Index des letzten passenden Zeichens oder -1, falls nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
