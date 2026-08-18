---
title: "System::Decimal::Round method"
linktitle: "Rund"
second_title: "Aspose.PUB für C++"
description: "System::Decimal::Round-Methode. Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion''s an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist, in C++."
type: docs
weight: 4400
url: /de/cpp/system/decimal/round/
---
## Decimal::Round(const Decimal\&, int, MidpointRounding) method


Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter legt das Verhalten der Funktion fest, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const Decimal\& | Der zu rundende Wert |
| Ziffern | int | Die Anzahl der Nachkommastellen im gerundeten Wert |
| Modus | MidpointRounding | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleich weit von beiden nächsten Zahlen entfernt ist. |

### ReturnValue

Die Zahl mit der angegebenen Anzahl von Ziffern, die **value** am nächsten liegt

## Siehe auch

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Decimal::Round(const Decimal\&, MidpointRounding) method


Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter legt das Verhalten der Funktion fest, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const Decimal\& | Der zu rundende Wert |
| Modus | MidpointRounding | Gibt an, wie das Runden durchgeführt wird, wenn **value** gleich weit von beiden nächsten Zahlen entfernt ist. |

### ReturnValue

**d** rounded to the nearest integral value

## Siehe auch

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
