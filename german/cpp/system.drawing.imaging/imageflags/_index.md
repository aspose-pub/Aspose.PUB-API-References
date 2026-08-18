---
title: "System::Drawing::Imaging::ImageFlags enum"
linktitle: "ImageFlags"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Imaging::ImageFlags enum. Stellt Attribute der von einem Image‑Objekt dargestellten Pixeldaten in C++ dar."
type: docs
weight: 2200
url: /de/cpp/system.drawing.imaging/imageflags/
---
## ImageFlags enum


Stellt Attribute der von einem [Image](../../system.drawing/image/)‑Objekt dargestellten Pixeldaten dar.

```cpp
enum class ImageFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 |  |
| Skalierbar | 1 | Skalierbar. |
| HasAlpha | 2 | Enthält Alpha‑Informationen. |
| HasTranslucent | 4 | Es gibt Alphawerte größer als 0 und kleiner als 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Die Pixeldaten werden im RGB-Farbraum dargestellt. |
| ColorSpaceCmyk | 32 | Die Pixeldaten werden im CMYK-Farbraum dargestellt. |
| ColorSpaceGray | 64 | Die Pixeldaten sind in Graustufen. |
| ColorSpaceYcbcr | 128 | Die Pixeldaten werden im YCBCR-Farbraum dargestellt. |
| ColorSpaceYcck | 256 | Die Pixeldaten werden im YCCK-Farbraum dargestellt. |
| HasRealDpi | 4096 | Die DPI-Informationen werden im Bild gespeichert. |
| HasRealPixelSize | 8192 | Die Größe eines Pixels wird im Bild gespeichert. |
| ReadOnly | 65536 | Die Pixeldaten sind schreibgeschützt. |
| Caching | 131072 | Kann für schnelleren Zugriff zwischengespeichert werden. |

## Siehe auch

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PUB for C++](../../)
