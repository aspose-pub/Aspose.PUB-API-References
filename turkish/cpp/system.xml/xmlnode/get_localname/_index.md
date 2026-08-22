---
title: "System::Xml::XmlNode::get_LocalName yöntemi"
linktitle: "get_LocalName"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNode::get_LocalName yöntemi. C++'ta türetilmiş bir sınıfta geçersiz kılındığında düğümün yerel adını döndürür."
type: docs
weight: 1400
url: /tr/cpp/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName method


Türetilmiş bir sınıfta geçersiz kılındığında, düğümün yerel adını döndürür.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### ReturnValue

Önek kaldırılmış düğümün adı. Örneğin, **LocalName** öğesi **<bk:book>** için **book** olur.
## Açıklamalar



Döndürülen ad, düğümün [XmlNode::get_NodeType](../get_nodetype/) değerine bağlıdır: |||
|-|-|
| Tür | Ad |
| Özellik | Özniteliğin yerel adı. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Belge türü adı. |
| Eleman | Öğenin yerel adı. |
| Entity | Varlığın adı. |
| EntityReference | Referans verilen varlığın adı. |
| Notation | Notasyon adı. |
| ProcessingInstruction | İşleme talimatının hedefi. |
| Metin | #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| XmlDeclaration | #xml-declaration |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
