---
title: "System::Drawing::CopyPixelOperation‑Enum"
linktitle: "CopyPixelOperation"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::CopyPixelOperation‑Enum. Gibt an, wie die Quellfarbe bei einer Pixelkopieroperation mit der Ziel­farbe kombiniert wird, um in C++ eine Endfarbe zu erhalten."
type: docs
weight: 3000
url: /de/cpp/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Gibt an, wie die Quellfarbe bei einer Pixelkopieroperation mit der Zielfarbe kombiniert wird, um eine Endfarbe zu erhalten.

```cpp
enum class CopyPixelOperation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Das Bitmap wird nicht gespiegelt. |
| Schwärze | 66 | Der Zielbereich wird mit der Farbe mit Index 0 in der physischen Palette gefüllt. |
| NotSourceErase | 1114278 | Die Quell‑ und Ziel­farben werden ODER‑verknüpft und die resultierende Farbe wird anschließend invertiert. |
| NotSourceCopy | 3342344 | Die Quellregion wird invertiert und dann in das Ziel kopiert. |
| SourceErase | 4457256 | Die invertierten Farben der Zielregion werden mit den Farben der Quellregion UND-verknüpft. |
| DestinationInvert | 5570569 | Die Zielregion wird invertiert. |
| PatInvert | 5898313 | Die Farben des aktuell im Zielgeräte‑Kontext ausgewählten Pinsels werden mit den Farben des Ziels XOR-verknüpft. |
| SourceInvert | 6684742 | Die Farben der Quell- und Zielregionen werden XOR-verknüpft. |
| SourceAnd | 8913094 | Die Farben der Quell- und Zielregionen werden UND-verknüpft. |
| MergePaint | 12255782 | Die Farben der invertierten Quellregion werden mit den Farben der Zielregion ODER-verknüpft. |
| MergeCopy | 12583114 | Die Farben der Quellregion werden mit den Farben des im Zielgeräte‑Kontext ausgewählten Pinsels UND-verknüpft. |
| SourceCopy | 13369376 | Der Quellbereich wird direkt in den Zielbereich kopiert. |
| SourcePaint | 15597702 | Die Farben des Quell- und Zielbereichs werden ODER-verknüpft. |
| PatCopy | 15728673 | Der aktuell im Zielgeräte-Kontext ausgewählte Pinsel wird in das Ziel-Bitmap kopiert. |
| PatPaint | 16452105 | Die Farben des aktuell im Zielgeräte-Kontext ausgewählten Pinsels werden mit den Farben des invertierten Quellbereichs ODER-verknüpft. Das Ergebnis dieser Operation wird mit den Farben des Zielbereichs ODER-verknüpft. |
| Whiteness | 16711778 | Der Zielbereich wird mit der Farbe mit Index 1 in der physischen Palette gefüllt. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) die über dem Anwendungsfenster geschichtet sind, werden in das resultierende Bild einbezogen. |

## Siehe auch

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
