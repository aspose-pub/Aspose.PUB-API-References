---
title: "System::Drawing::Bitmap::LockBits Methode"
linktitle: "LockBits"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Bitmap::LockBits Methode. Sperrt ein Bitmap in den Systemspeicher in C++."
type: docs
weight: 1500
url: /de/cpp/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method


Sperrt ein [Bitmap](../) in den Systemspeicher.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const Rectangle\& | Ein Rechteck, das den zu sperrenden Bildbereich angibt |
| Flags | Imaging::ImageLockMode | Gibt die Zugriffsebene auf das Bitmap an |
| Format | Imaging::PixelFormat | Das Datenformat dieses Bitmaps |

### ReturnValue

Ein Shared Pointer auf ein BitmapData-Objekt, das Informationen über die durchgeführte Sperroperation enthält

## Siehe auch

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method


Sperrt ein [Bitmap](../) in den Systemspeicher.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const Rectangle\& | Ein Rechteck, das den zu sperrenden Bildbereich angibt |
| Flags | Imaging::ImageLockMode | Gibt die Zugriffsebene auf das Bitmap an |
| Format | Imaging::PixelFormat | Das Datenformat dieses Bitmaps |
| bitmap_data | const Imaging::BitmapDataPtr\& | Enthält Informationen über die Sperroperation |

### ReturnValue

Ein Shared Pointer auf ein BitmapData-Objekt, das Informationen über die durchgeführte Sperroperation enthält

## Siehe auch

* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
