---
title: "System::Drawing::Graphics::MeasureString method"
linktitle: "MeasureString"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Graphics::MeasureString method. C++'ta belirtilen biçimde, belirtilen yazı tipinde çizildiğinde belirtilen dizeyin boyutunu döndürür."
type: docs
weight: 6500
url: /tr/cpp/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method


Belirtilen dize, belirtilen yazı tipinde ve belirtilen biçimde çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String const\& | Boyutu hesaplanacak dize |
| yazı tipi | System::SharedPtr\<Font\> const\& | Dizeyi çizmek için kullanılan yazı tipi |
| genişlik | int | Dizenin maksimum genişliği |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Dize biçimini belirtir |

### ReturnValue

Geçerli Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dizeyi temsil eden bir [SizeF](../../sizef/) nesnesi.

## Ayrıca Bakınız

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Belirtilen dize, belirtilen yazı tipinde ve belirtilen biçimde çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String const\& | Boyutu hesaplanacak dize |
| yazı tipi | System::SharedPtr\<Font\> const\& | Dizeyi çizmek için kullanılan yazı tipi |
| origin | PointF const\& | Dizenin sol üst köşesinin konumunu belirtir |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Dize biçimini belirtir |

### ReturnValue

Geçerli Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dizeyi temsil eden bir [SizeF](../../sizef/) nesnesi.

## Ayrıca Bakınız

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method


UYGULANMADI.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Ayrıca Bakınız

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Belirtilen dize, belirtilen yazı tipinde ve belirtilen biçimde çizildiğinde boyutunu döndürür.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String const\& | Boyutu hesaplanacak dize |
| yazı tipi | System::SharedPtr\<Font\> const\& | Dizeyi çizmek için kullanılan yazı tipi |
| layoutArea | SizeF const\& | Dizenin maksimum yerleşim alanı |
| stringFormat | System::SharedPtr\<StringFormat\> const\& | Dize biçimini belirtir |

### ReturnValue

Geçerli Graphics nesnesinin PageUnit özelliği tarafından belirtilen ölçüm birimlerinde dizeyi temsil eden bir [SizeF](../../sizef/) nesnesi.

## Ayrıca Bakınız

* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../../font/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PUB for C++](../../../)
