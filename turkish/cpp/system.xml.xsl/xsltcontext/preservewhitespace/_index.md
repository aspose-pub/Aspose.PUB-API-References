---
title: "System::Xml::Xsl::XsltContext::PreserveWhitespace metodu"
linktitle: "PreserveWhitespace"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XsltContext::PreserveWhitespace metodu. Türetilmiş bir sınıfta geçersiz kılındığında, verilen bağlamda boşluk düğümlerini koruyup korumayacağını veya kaldırıp kaldırmayacağını C++'da değerlendirir."
type: docs
weight: 300
url: /tr/cpp/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace method


Türetilmiş bir sınıfta geçersiz kılındığında, verilen bağlam için boşluk düğümlerinin korunup korunmayacağını değerlendirir.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Geçerli bağlamda korunacak veya kaldırılacak boşluk düğümü. |

### ReturnValue

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
