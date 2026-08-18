---
title: "Klasse Aspose::Pub::TextPartDisplayParams"
linktitle: "TextPartDisplayParams"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::TextPartDisplayParams Klasse. Entwickelt, um Text zu halten, der für Endbenutzer angezeigt werden soll. Fälle wie das Dokument 383.pub erzeugen eine Situation, in der der Originaltext aus dem Publisher-Dokument nicht ohne Änderungen den Endbenutzern angezeigt werden kann. Im Moment reicht es aus, einfach die modifizierte Version des Originaltexts zu halten, die sich vom Original nur in Unicode‑Werten unterscheidet, aber künftig könnten Fälle auftreten, in denen die modifizierte Version nicht nur in Unicode, sondern auch in Textlänge und Ähnlichem vom Original abweicht. Wenn solche Fälle auftreten, sollte diese Klasse angepasst werden, um den neuen Anforderungen an angezeigten Text in C++ gerecht zu werden."
type: docs
weight: 3600
url: /de/cpp/aspose.pub/textpartdisplayparams/
---
## TextPartDisplayParams class


Entwickelt, um Text zu halten, der für Endbenutzer angezeigt werden soll. Fälle wie das Dokument 383.pub erzeugen eine Situation, in der der Originaltext aus dem Publisher-Dokument nicht ohne Änderungen den Endbenutzern angezeigt werden kann. Im Moment reicht es aus, einfach die modifizierte Version des Originaltexts zu speichern, die sich vom Original nur in Unicode-Werten unterscheidet, aber künftig könnten Fälle auftreten, in denen die modifizierte Version nicht nur in Unicode, sondern auch in Textlänge und Ähnlichem vom Original abweicht. Wenn solche Fälle auftreten, sollte diese Klasse angepasst werden, um den neuen Anforderungen an den angezeigten Text gerecht zu werden.

```cpp
class TextPartDisplayParams : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Font](./get_font/)() const | Schriftart des Textteils. |
| [get_FontSize](./get_fontsize/)() const | Schriftgröße des Textteils. |
| [get_Text](./get_text/)() const | Text. |
| [get_TextStyle](./get_textstyle/)() const | Textstil. |
| [SetFontData](./setfontdata/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, float) |  |
| [TextPartDisplayParams](./textpartdisplayparams/)(System::String, System::SharedPtr\<Aspose::Pub::TextStyle\>) | Konstruktor. |
| [UpdateText](./updatetext/)(System::String) | Aktualisiert Text. |
| [UpdateTextStyle](./updatetextstyle/)(System::SharedPtr\<Aspose::Pub::TextStyle\>) |  |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
