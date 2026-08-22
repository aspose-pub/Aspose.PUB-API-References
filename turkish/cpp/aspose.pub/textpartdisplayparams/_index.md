---
title: "Aspose::Pub::TextPartDisplayParams sınıfı"
linktitle: "TextPartDisplayParams"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::TextPartDisplayParams sınıfı. Son kullanıcılar için görüntülenmesi gereken metni tutmak üzere tasarlanmıştır. 383.pub gibi belgeler, Publisher belgesinden gelen orijinal metnin değişiklik yapılmadan son kullanıcılara gösterilemediği bir durum ortaya çıkarır. Şu anda, yalnızca Unicode değerlerinde farklılık gösteren orijinal metnin değiştirilmiş sürümünü tutmak yeterlidir, ancak ileride değiştirilmiş sürümün sadece Unicode değerlerinde değil, metin uzunluğunda ve benzeri konularda da orijinalden farklı olabileceği durumlar olabilir. Böyle durumlar ortaya çıkarsa, bu sınıf C++'ta görüntülenen metin için yeni gereksinimlere uyacak şekilde değiştirilmelidir."
type: docs
weight: 3600
url: /tr/cpp/aspose.pub/textpartdisplayparams/
---
## TextPartDisplayParams class


Son kullanıcılar için görüntülenmesi gereken metni tutmak üzere tasarlanmıştır. 383.pub gibi belgeler, Publisher belgesinin orijinal metninin değişiklik yapılmadan son kullanıcılara gösterilemediği bir durum ortaya çıkarır. Şu anda, yalnızca Unicode değerlerinde farklılık gösteren, orijinal metnin değiştirilmiş sürümünü basitçe tutmak yeterlidir; ancak ileride, değiştirilmiş sürümün yalnızca Unicode'larda değil, metin uzunluğunda ve benzeri konularda da orijinalden farklı olabileceği durumlar ortaya çıkabilir. Böyle durumlar ortaya çıkarsa, bu sınıf görüntülenen metin için yeni gereksinimlere uyacak şekilde değiştirilmelidir.

```cpp
class TextPartDisplayParams : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Font](./get_font/)() const | Metin parçasının fontu. |
| [get_FontSize](./get_fontsize/)() const | Metin parçasının font boyutu. |
| [get_Text](./get_text/)() const | Metin. |
| [get_TextStyle](./get_textstyle/)() const | Metin stili. |
| [SetFontData](./setfontdata/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, float) |  |
| [TextPartDisplayParams](./textpartdisplayparams/)(System::String, System::SharedPtr\<Aspose::Pub::TextStyle\>) | Yapıcı. |
| [UpdateText](./updatetext/)(System::String) | Metni günceller. |
| [UpdateTextStyle](./updatetextstyle/)(System::SharedPtr\<Aspose::Pub::TextStyle\>) |  |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
