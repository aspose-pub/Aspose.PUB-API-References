---
title: "System::Drawing::Imaging::PixelFormat enum"
linktitle: "PixelFormat"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Imaging::PixelFormat enum. Gibt das Farbdatumsformat eines Pixels in C++ an."
type: docs
weight: 2600
url: /de/cpp/system.drawing.imaging/pixelformat/
---
## PixelFormat enum


Gibt das Farbdatenformat eines Pixels an.

```cpp
enum class PixelFormat
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Indexed | 65536 | Gibt an, dass die Pixeldaten farbindizierte Werte enthalten, was bedeutet, dass sie einen Index zu Farben in der Systemfarbtabelle darstellen. |
| Gdi | 131072 | Gibt an, dass die Pixeldaten GDI‑Farben enthalten. |
| Alpha | 262144 | Gibt an, dass die Pixeldaten Alphawerte enthalten, die nicht vorab multipliziert sind. |
| PAlpha | 524288 | Gibt an, dass die Pixeldaten vorab multiplizierte Alphawerte enthalten. |
| Extended | 1048576 | Reserviert. |
| Canonical | 2097152 | Gibt das Pixelformat von 32 Bit pro Pixel mit einer Farbtiefe von 24 Bit und einem 8‑Bit‑Alphakanal an. |
| Undefined | 0 | Gibt an, dass das Pixelformat undefiniert ist. |
| DontCare | 0 | Das Pixelformat ist nicht angegeben. |
| Format1bppIndexed | n/a | Gibt an, dass das Pixelformat indizierte Farbe mit 1 Bit pro Pixel ist. |
| Format4bppIndexed | n/a | Gibt an, dass das Pixelformat indizierte Farbe mit 4 Bit pro Pixel ist. |
| Format8bppIndexed | n/a | Gibt an, dass das Pixelformat indizierte Farbe mit 8 Bit pro Pixel ist. |
| Format16bppGrayScale | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel beträgt. Die Farbinformation gibt 65536 Graustufen an. |
| Format16bppRgb555 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit je 5 Bit für die Rot-, Grün- und Blaukomponenten hat und das verbleibende Bit nicht verwendet wird. |
| Format16bppRgb565 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit 5 Bit für Rot, 6 Bit für Grün und 5 Bit für Blaukomponenten hat. |
| Format16bppArgb1555 | n/a | Gibt an, dass das Pixelformat 16 Bit pro Pixel mit je 5 Bit für Rot-, Grün- und Blaukomponenten und 1 Bit für Alpha hat. |
| Format24bppRgb | n/a | Gibt an, dass das Pixelformat 24 Bit pro Pixel mit je 8 Bit für Rot-, Grün- und Blaukomponenten beträgt. |
| Format32bppRgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit je 8 Bit für Rot-, Grün- und Blaukomponenten und den verbleibenden 8 Bit nicht verwendet werden. |
| Format32bppArgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit 8 Bit für jede der roten, grünen und blauen Komponenten und 8 Bit für Alpha ist. |
| Format32bppPArgb | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit 8 Bit für jede der roten, grünen und blauen Komponenten und 8 Bit für Alpha ist. Die roten, grünen und blauen Komponenten sind gemäß dem Wert der Alpha‑Komponente vorgemultipliziert. |
| Format48bppRgb | n/a | Gibt an, dass das Pixelformat 48 Bit pro Pixel mit 16 Bit für jede der roten, grünen und blauen Komponenten ist. |
| Format64bppArgb | n/a | Gibt an, dass das Pixelformat 64 Bit pro Pixel mit 16 Bit für jede der roten, grünen und blauen Komponenten und 16 Bit für Alpha ist. |
| Format64bppPArgb | n/a | Gibt an, dass das Pixelformat 64 Bit pro Pixel mit 16 Bit für jede der roten, grünen und blauen Komponenten und 16 Bit für Alpha ist. Die roten, grünen und blauen Komponenten sind gemäß dem Wert der Alpha‑Komponente vorgemultipliziert. |
| Format32bppCMYK | n/a | Gibt an, dass das Pixelformat 32 Bit pro Pixel mit 8 Bit für jede der Cyan-, Magenta-, Gelb- und Schwarz‑Komponenten ist. |
| Max | 16 | Der Maximalwert dieses Enums. |

## Siehe auch

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
