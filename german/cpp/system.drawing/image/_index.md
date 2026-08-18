---
title: "System::Drawing::Image-Klasse"
linktitle: "Image"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Image-Klasse. Eine Basisklasse für die Klassen System::Drawing::Bitmap und System::Drawing::Metafile, die grundlegende Funktionalität bereitstellt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1200
url: /de/cpp/system.drawing/image/
---
## Image class


Eine Basisklasse für die Klassen [System::Drawing::Bitmap](../bitmap/) und System::Drawing::Metafile, die grundlegende Funktionalität bereitstellt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Image : public virtual System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Clone](./clone/)() | Erstellt eine Kopie des aktuellen Objekts. |
| [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt erworbenen Ressourcen frei. |
| static [FromFile](./fromfile/)(const String\&, bool) | Erstellt ein [Image](./)-Objekt aus der angegebenen Datei. |
| static [FromHbitmap](./fromhbitmap/)(IntPtr) | Erzeugt ein [Bitmap](../bitmap/)-Objekt aus dem angegebenen GDI-Bitmap. |
| static [FromStream](./fromstream/)(const SharedPtr\<System::IO::Stream\>\&, bool, bool) | Erstellt ein [Image](./)-Objekt aus dem angegebenen Stream. |
| virtual [get_Flags](./get_flags/)() const | Gibt eine bitweise Kombination von ImageFlags-Enum-Werten zurück, die die Attribute des Bildes darstellen. |
| [get_FrameDimensionsList](./get_framedimensionslist/)() const | Gibt ein Array von GUIDs zurück, das die Abmessungen der Frames im Bild des aktuellen Objekts darstellt. |
| virtual [get_Height](./get_height/)() const | Gibt die Höhe des Bildes in Pixeln zurück. |
| [get_HorizontalResolution](./get_horizontalresolution/)() const | Gibt die horizontale Auflösung des vom aktuellen Objekt dargestellten Bildes in Pixel pro Zoll zurück. |
| virtual [get_Palette](./get_palette/)() const | Gibt die vom aktuellen Objekt dargestellte Farbtabelle des Bildes zurück. |
| virtual [get_PixelFormat](./get_pixelformat/)() const | Gibt das Pixelformat des vom aktuellen Objekt dargestellten Bildes zurück. |
| virtual [get_PropertyIdList](./get_propertyidlist/)() const | Ermittelt die IDs der in diesem Bild gespeicherten Property-Elemente. |
| virtual [get_PropertyItems](./get_propertyitems/)() const | Ermittelt alle Property-Elemente (Metadatenstücke), die in diesem Bild gespeichert sind. |
| virtual [get_RawFormat](./get_rawformat/)() const | Gibt das Dateiformat des vom aktuellen Objekt dargestellten Bildes zurück. |
| [get_Size](./get_size/)() const | Gibt ein [Size](../size/)-Objekt zurück, das die Breite und Höhe des Bildes in Pixeln darstellt. |
| virtual [get_Tag](./get_tag/)() const | Ermittelt ein Objekt, das zusätzliche Daten über das Bild bereitstellt. |
| [get_VerticalResolution](./get_verticalresolution/)() const | Gibt die vertikale Auflösung des vom aktuellen Objekt dargestellten Bildes in Pixel pro Zoll zurück. |
| virtual [get_Width](./get_width/)() const | Gibt die Breite des Bildes in Pixeln zurück. |
| [GetBounds](./getbounds/)(GraphicsUnit\&) | Gibt die Bildgrenzen in den angegebenen Maßeinheiten zurück. |
| [GetFrameCount](./getframecount/)(const Imaging::FrameDimensionPtr\&) | Gibt die Anzahl der Frames der angegebenen Frame-Dimension zurück. |
| static [GetPixelFormatSize](./getpixelformatsize/)(Imaging::PixelFormat) | Gibt die Anzahl der Bits zurück, die zur Darstellung der Farbtiefe im angegebenen Pixelformat verwendet werden. |
| virtual [GetSkBitmap](./getskbitmap/)() const | Gibt ein zugrunde liegendes SkBitmap-Objekt zurück. |
| [GetThumbnailImage](./getthumbnailimage/)(int, int, Image::GetThumbnailImageAbort, IntPtr) | Ermittelt ein Thumbnail für dieses [System::Drawing::Image](./)-Objekt. |
| static [IsAlphaPixelFormat](./isalphapixelformat/)(Imaging::PixelFormat) | Bestimmt, ob das angegebene Pixelformat Alphainformationen enthält. |
| virtual [IsMultiImage](./ismultiimage/)() const | Gibt zurück, ob das Originalformat ein Mehrfachbild ist. |
| virtual [RotateFlip](./rotateflip/)(RotateFlipType) | Bild um ein Vielfaches von 90 Grad drehen und spiegeln. |
| [Save](./save/)(const String\&) | Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei im PNG-Format. |
| [Save](./save/)(const String\&, const Imaging::ImageFormatPtr\&) | Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei im angegebenen Format. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) | Speichert das durch das aktuelle Objekt dargestellte Bild in den angegebenen Stream im angegebenen Format. |
| [Save](./save/)(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Speichert das durch das aktuelle Objekt dargestellte Bild in die angegebene Datei unter Verwendung des angegebenen Encoders und der Encoder-Parameter. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Speichert das durch das aktuelle Objekt dargestellte Bild in den angegebenen Stream unter Verwendung des angegebenen Encoders und der Encoder-Parameter. |
| [SaveAdd](./saveadd/)(const Imaging::EncoderParametersPtr\&) | Fügt dem in einem vorherigen Aufruf der Methode [Save()](./save/) angegebenen Datei- oder Stream-Objekt einen Frame hinzu. |
| [SaveAdd](./saveadd/)(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) | Fügt dem in einem vorherigen Aufruf der Methode [Save()](./save/) angegebenen Datei- oder Stream-Objekt einen Frame hinzu. |
| [SelectActiveFrame](./selectactiveframe/)(const Imaging::FrameDimensionPtr\&, int) | Wählt den angegebenen Frame aus. |
| virtual [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) | Legt die vom durch das aktuelle Objekt dargestellten Bild verwendete Farbpalette fest. |
| virtual [set_Tag](./set_tag/)(const System::SharedPtr\<System::Object\>) | Legt ein Objekt fest, das zusätzliche Daten zum Bild bereitstellt. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Ein Rückruf, um die Ausführung von GetThumbnailImage abzubrechen. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
