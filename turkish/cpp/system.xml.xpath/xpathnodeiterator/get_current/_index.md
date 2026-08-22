---
title: "System::Xml::XPath::XPathNodeIterator::get_Current yöntemi"
linktitle: "get_Current"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNodeIterator::get_Current yöntemi. Türetilmiş bir sınıfta geçersiz kılındığında, C++'ta bu XPathNodeIterator için geçerli bağlam düğümünde konumlandırılmış XPathNavigator nesnesini alır."
type: docs
weight: 400
url: /tr/cpp/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current method


Türetilmiş bir sınıfta geçersiz kılındığında, bu [XPathNodeIterator](../) için geçerli bağlam düğümünde konumlandırılmış [XPathNavigator](../../xpathnavigator/) nesnesini alır.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### ReturnValue

Seçilen düğüm kümesinin alındığı bağlam düğümünde konumlandırılmış bir [XPathNavigator](../../xpathnavigator/) nesnesi. Seçilen kümedeki ilk düğüme [XPathNodeIterator](../) geçmek için [XPathNodeIterator::MoveNext](../movenext/) yönteminin çağrılması gerekir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../xpathnavigator/)
* Class [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PUB for C++](../../../)
