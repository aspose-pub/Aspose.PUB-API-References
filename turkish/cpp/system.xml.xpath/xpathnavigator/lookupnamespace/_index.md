---
title: "System::Xml::XPath::XPathNavigator::LookupNamespace yöntemi"
linktitle: "LookupNamespace"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNavigator::LookupNamespace yöntemi. Belirtilen önek için C++'ta ad alanı URI'sini döndürür."
type: docs
weight: 4700
url: /tr/cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace method


Belirtilen önek için isim alanı URI'sını döndürür.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const String\& | Çözmek istediğiniz ad alanı URI'sına sahip önek. Varsayılan ad alanıyla eşleşmek için [String::Empty](../../../system/string/empty/) değerini geçirin. |

### ReturnValue

Belirtilen ad alanı önekine atanmış ad alanı URI'sini içeren bir [String](../../../system/string/); **nullptr** eğer belirtilen önek için ad alanı URI'si atanmadıysa. Döndürülen [String](../../../system/string/) atomizedir.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
