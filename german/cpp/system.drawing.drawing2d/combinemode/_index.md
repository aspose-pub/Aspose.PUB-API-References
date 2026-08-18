---
title: "System::Drawing::Drawing2D::CombineMode Enum"
linktitle: "CombineMode"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Drawing2D::CombineMode Enum. Gibt an, wie Clip‑Regionen in C++ kombiniert werden."
type: docs
weight: 1400
url: /de/cpp/system.drawing.drawing2d/combinemode/
---
## CombineMode enum


Gibt an, wie Beschneidungsregionen kombiniert werden.

```cpp
enum class CombineMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Ersetzen | 0 | Eine Clip‑Region wird durch eine andere ersetzt. |
| Schnittmenge | 1 | Die beiden Clip‑Regionen werden durch Bilden ihrer Schnittmenge kombiniert. |
| Union | 2 | Die beiden Clip‑Regionen werden durch Bilden ihrer Vereinigung kombiniert. |
| Xor | 3 | Die beiden Clip‑Regionen werden kombiniert, indem nur der Bereich genommen wird, der von einer der beiden Regionen eingeschlossen ist, jedoch nicht von beiden. |
| Ausschließen | 4 | Zwei Clip‑Regionen werden kombiniert, indem der Bereich der ersten Region genommen wird, der nicht mit der zweiten überschneidet. |
| Komplement | 5 | Zwei Clip‑Regionen werden kombiniert, indem der Bereich der zweiten Region genommen wird, der nicht mit der ersten überschneidet. |

## Siehe auch

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PUB for C++](../../)
