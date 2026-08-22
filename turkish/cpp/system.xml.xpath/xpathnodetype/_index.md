---
title: "System::Xml::XPath::XPathNodeType enum"
linktitle: "XPathNodeType"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNodeType enum. C++'ta XPathNavigator sınıfından döndürülebilecek XPath düğüm türlerini tanımlar."
type: docs
weight: 1100
url: /tr/cpp/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum


Bu, [XPath](../) düğüm türlerini tanımlar ve [XPathNavigator](../xpathnavigator/) sınıfından döndürülebilir.

```cpp
enum class XPathNodeType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Kök | 0 | XML belgesinin veya düğüm ağacının kök düğümü. |
| Eleman | 1 | Bir öğe, örneğin **<element>**. |
| Özellik | 2 | Bir öznitelik, örneğin **id='123'**. |
| Ad alanı | 3 | Bir ad alanı, örneğin **xmlns=\"namespace\"**. |
| Text | 4 | Bir düğümün metin içeriği. Belge [Object](../../system/object/) Modeli (DOM) [Text](../../system.text/) ve CDATA düğüm türlerine eşdeğerdir. En az bir karakter içerir. |
| SignificantWhitespace | 5 | Beyaz boşluk karakterleri içeren ve **xml:space** değeri **preserve** olarak ayarlanmış bir düğüm. |
| Whitespace | 6 | Yalnızca beyaz boşluk karakterleri içeren ve anlamlı boşluk bulunmayan bir düğüm. Beyaz boşluk karakterleri **'\\x20'**, **'\\x0d'**, **'\\x0a'**, **'\\x09'**. |
| ProcessingInstruction | 7 | Bir işleme talimatı, örneğin **<?pi test?>**. Bu, [XPathNavigator](../xpathnavigator/) sınıfı tarafından görülmeyen XML bildirimlerini içermez. |
| Comment | 8 | Bir yorum, örneğin ****. |
| Tümü | 9 | XPathNodeType düğüm türlerinden herhangi biri. |

## Ayrıca Bakınız

* Namespace [System::Xml::XPath](../)
* Library [Aspose.PUB for C++](../../)
