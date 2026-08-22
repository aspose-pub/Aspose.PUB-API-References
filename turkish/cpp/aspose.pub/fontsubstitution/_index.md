---
title: "Aspose::Pub::FontSubstitution sınıfı"
linktitle: "FontSubstitution"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::FontSubstitution sınıfı. C++'ta font adına dayalı bir font değiştirme stratejisi için sınıfı temsil eder."
type: docs
weight: 900
url: /tr/cpp/aspose.pub/fontsubstitution/
---
## FontSubstitution class


Yazı tipi adına dayalı bir yazı tipi ikame stratejisi için bir sınıfı temsil eder.

```cpp
class FontSubstitution : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [FontSubstitution](./fontsubstitution/)(System::String, System::String, bool) | Yeni bir [SimpleFontSubstitution](../) sınıf örneği başlatır. |
| [get_OriginalFontName](./get_originalfontname/)() const | Orijinal font adını alır; bu, [SubstitutionFontName](../) ile değiştirilmelidir. |
| [get_ReplaceAlways](./get_replacealways/)() const | Fontların her zaman değiştirilip değiştirilmeyeceğini belirtir. False olarak ayarlanırsa, fontlar yalnızca [OriginalFontName](../) parametresiyle belirtilen adın hedef PC'de bulunmaması durumunda değiştirilir. |
| [get_SubstitutionFontName](./get_substitutionfontname/)() const | [OriginalFontName](../) öğesini değiştirecek font adını alır. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
