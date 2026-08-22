---
title: "System::Drawing::Text::PrivateFontCollection class"
linktitle: "PrivateFontCollection"
second_title: "Aspose.PUB için C++"
description: "System::Drawing::Text::PrivateFontCollection class. İstemci uygulaması tarafından sağlanan yazı tipi ailelerinin bir koleksiyonunu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 300
url: /tr/cpp/system.drawing.text/privatefontcollection/
---
## PrivateFontCollection class


İstemci uygulaması tarafından sağlanan yazı tipi ailelerinin bir koleksiyonunu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class PrivateFontCollection : public System::Drawing::Text::FontCollection
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddFont](./addfont/)(const System::ArrayPtr\<uint8_t\>\&, int) | Belirtilen yazı tipini koleksiyona ekler. |
| [AddFontFile](./addfontfile/)(const String\&) | Belirtilen dosyadan bir yazı tipini koleksiyona ekler. |
| [get_Families](./get_families/)() override | Geçerli nesne tarafından temsil edilen yazı tipi koleksiyonu ile ilişkili [FontFamily](../../system.drawing/fontfamily/) nesnelerinden oluşan bir dizi döndürür. |
## Ayrıca Bakınız

* Class [FontCollection](../fontcollection/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PUB for C++](../../)
