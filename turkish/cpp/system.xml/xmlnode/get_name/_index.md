---
title: "System::Xml::XmlNode::get_Name yöntemi"
linktitle: "get_Name"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNode::get_Name yöntemi. C++'da türetilmiş bir sınıfta geçersiz kılındığında, düğümün nitelikli adını döndürür."
type: docs
weight: 1500
url: /tr/cpp/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name method


Türetilmiş bir sınıfta geçersiz kılındığında, düğümün nitelikli adını döndürür.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### ReturnValue

Düğümün nitelikli adı.
## Açıklamalar



Döndürülen ad, düğümün [XmlNode::get_NodeType](../get_nodetype/) değerine bağlıdır: |||
|-|-|
| Tür | Ad |
| Özellik | Niteliğin nitelikli adı. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Belge türü adı. |
| Eleman | Elemanın nitelikli adı. |
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
