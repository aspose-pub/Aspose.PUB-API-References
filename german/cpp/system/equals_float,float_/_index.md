---
title: "System::Equals< float, float > Methode"
linktitle: "Equals< float, float >"
second_title: "Aspose.PUB für C++"
description: "System::Equals< float, float > Methode. Spezialisierung für Gleitkommawerte mit einfacher Genauigkeit. Obwohl zwei Gleitkomma‑NaNs gemäß IEC 60559:1989 immer als ungleich verglichen werden, verlangt der Vertrag für System.Object.Equals, dass Überschreibungen die Anforderungen eines Äquivalenzoperators erfüllen. Daher geben System.Double.Equals und System.Single.Equals True zurück, wenn zwei NaNs verglichen werden, während der Gleichheitsoperator in diesem Fall False zurückgibt, wie es der Standard in C++ vorsieht."
type: docs
weight: 17300
url: /de/cpp/system/equals_float,float_/
---
## System::Equals< float, float > method


Spezialisierung für Gleitkommawerte mit einfacher Genauigkeit. Obwohl zwei Gleitkomma‑NaNs gemäß IEC 60559:1989 immer als ungleich verglichen werden, verlangt der Vertrag für [System.Object.Equals](../object/equals/), dass Überschreibungen die Anforderungen eines Äquivalenzoperators erfüllen. Daher geben System.Double.Equals und System.Single.Equals True zurück, wenn zwei NaNs verglichen werden, während der Gleichheitsoperator in diesem Fall False zurückgibt, wie es der Standard verlangt.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const float\& | Der erste Operand |
| b | const float\& | Der zweite Operand |

### ReturnValue

True, wenn beide Werte NaN sind oder gleich sind, sonst - false

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
