---
title: "System::Xml::XPath::XPathNodeIterator class"
linktitle: "XPathNodeIterator"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathNodeIterator class. C++'da seçilmiş bir düğüm kümesi üzerinde yineleyici sağlar."
type: docs
weight: 600
url: /tr/cpp/system.xml.xpath/xpathnodeiterator/
---
## XPathNodeIterator class


Seçili bir düğüm kümesi üzerinde bir yineleyici sağlar.

```cpp
class XPathNodeIterator : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XPath::XPathNavigator>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Clone](./clone/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu [XPathNodeIterator](./) nesnesinin bir kopyasını döndürür. |
| virtual [get_Count](./get_count/)() | Seçilen düğüm kümesindeki son düğümün indeksini döndürür. |
| virtual [get_Current](./get_current/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu [XPathNodeIterator](./) için mevcut bağlam düğümünde konumlandırılmış [XPathNavigator](../xpathnavigator/) nesnesini alır. |
| virtual [get_CurrentPosition](./get_currentposition/)() | Türetilmiş bir sınıfta geçersiz kılındığında, seçilen düğüm kümesindeki mevcut konumun indeksini alır. |
| [GetEnumerator](./getenumerator/)() override | Seçilen düğüm kümesi üzerinde yineleme yapmak için bir IEnumerator nesnesi döndürür. |
| virtual [MoveNext](./movenext/)() | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNodeIterator::get_Current](./get_current/) yöntemi tarafından döndürülen [XPathNavigator](../xpathnavigator/) nesnesini seçilen düğüm kümesindeki bir sonraki düğüme taşır. |
| [XPathNodeIterator](./xpathnodeiterator/)() | [XPathNodeIterator](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PUB for C++](../../)
