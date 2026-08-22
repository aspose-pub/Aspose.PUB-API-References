---
title: "System::Xml::XPath::XPathNavigator::AppendChildElement yöntemi"
linktitle: "AppendChildElement"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::AppendChildElement yöntemi. Belirtilen ad alanı öneki, yerel ad ve ad alanı URI'si ile C++'ta belirtilen değeri kullanarak mevcut düğümün alt düğüm listesi sonuna yeni bir alt öğe düğümü oluşturur."
type: docs
weight: 200
url: /tr/cpp/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement method


Belirtilen ad alanı öneki, yerel ad ve ad alanı URI'si ile birlikte verilen değeri kullanarak geçerli düğümün alt düğüm listesi sonunda yeni bir alt öğe düğümü oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| önek | String | Yeni alt öğe düğümünün ad alanı öneki (varsa). |
| localName | String | Yeni alt öğe düğümünün yerel adı (varsa). |
| namespaceURI | String | Yeni alt öğe düğümünün ad alanı URI'si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| value | String | Yeni alt öğe düğümünün değeri. Eğer [String::Empty](../../../system/string/empty/) veya **nullptr** geçirilirse, boş bir öğe oluşturulur. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
