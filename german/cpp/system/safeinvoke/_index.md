---
title: "System::SafeInvoke method"
linktitle: "SafeInvoke"
second_title: "Aspose.PUB für C++"
description: "System::SafeInvoke method. Implementierung der ''?.''‑Operator‑Übersetzung in C++."
type: docs
weight: 33500
url: /de/cpp/system/safeinvoke/
---
## System::SafeInvoke method


Implementierung der '?.'-Operator‑Übersetzung.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 expr, T1 func)
```


| Parameter | Beschreibung |
| --- | --- |
| T0 | Ausdruckstyp. |
| T1 | Typ des Lambdas, das den Ausdruck 'WhenTrue' kapselt. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausdruck | T0 | Ausdruckswert. |
| Funktion | T1 | 'WhenTrue' Ausdruck an Funktor gebunden. |

### ReturnValue

Wenn expr-Wert nicht null ist, wird func mit seinem Wert als erstem Argument aufgerufen und zurückgegeben, andernfalls wird null zurückgegeben.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
