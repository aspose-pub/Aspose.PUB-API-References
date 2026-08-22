---
title: "System::Drawing::Graphics::MeasureCharacterRanges yöntemi"
linktitle: "MeasureCharacterRanges"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Graphics::MeasureCharacterRanges yöntemi. C++'de belirtilen dizedeki karakter konumlarını sınırlayan bölgelerin bir dizisini döndürür."
type: docs
weight: 6400
url: /tr/cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges method


Belirtilen dizedeki karakter konumlarını sınırlayan bölgelerden oluşan bir dizi döndürür.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | const System::String\& | Ölçülecek dize |
| yazı tipi | const SharedPtr\<Font\>\& | Dize ölçümü sırasında kullanılan yazı tipi |
| layoutRect | RectangleF | Dize ölçümü sırasında kullanılan yerleşim dikdörtgeni |
| stringFormat | const SharedPtr\<StringFormat\>\& | Dize biçimi, ölçülecek karakter aralıklarını içerir |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
