---
title: "System::Char::IsSurrogatePair-Methode"
linktitle: "IsSurrogatePair"
second_title: "Aspose.PUB für C++"
description: "System::Char::IsSurrogatePair-Methode. Bestimmt, ob die beiden angegebenen Zeichen ein UTF‑16‑Surrogate‑Paar in C++ bilden."
type: docs
weight: 1700
url: /de/cpp/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method


Bestimmt, ob die beiden angegebenen Zeichen ein UTF-16-Surrogat-Paar bilden.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| highSurrogate | char_t | Ein Zeichen, das darauf getestet wird, ein High Surrogate zu sein |
| lowSurrogate | char_t | Ein Zeichen, das darauf getestet wird, ein Low Surrogate zu sein |

### ReturnValue

Wahr, wenn die angegebenen Zeichen ein Surrogate‑Paar bilden, sonst - falsch

## Siehe auch

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Char::IsSurrogatePair(const String\&, int) method


Bestimmt, ob zwei aufeinanderfolgende Zeichen im angegebenen Zeichenpuffer ein Surrogat-Paar bilden.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | Ein String |
| Index | int | Ein nullbasierter Index im angegebenen Puffer, an dem die zu testende Zeichenfolge beginnt |

### ReturnValue

Wahr, wenn die angegebenen Zeichen ein Surrogate‑Paar sind, sonst - falsch

## Siehe auch

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
