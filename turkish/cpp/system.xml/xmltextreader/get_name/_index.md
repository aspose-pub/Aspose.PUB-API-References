---
title: "System::Xml::XmlTextReader::get_Name yöntemi"
linktitle: "get_Name"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::get_Name yöntemi. Geçerli düğümün nitelikli adını C++'ta döndürür."
type: docs
weight: 1900
url: /tr/cpp/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name method


Geçerli düğümün nitelikli adını döndürür.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### ReturnValue

Geçerli düğümün nitelikli adı. Örneğin, **Name**, **bk:book** öğesidir **<bk:book>** öğesi için.
## Açıklamalar



Dönen ad, düğümün [XmlTextReader::get_NodeType](../get_nodetype/) değerine bağlıdır. Aşağıdaki düğüm tipleri listelenen değerleri döndürür. Diğer tüm düğüm tipleri boş bir dize döndürür. |||
|-|-|
| Düğüm Türü | Ad |
| Özellik | Özelliğin adı. |
| DocumentType | Belge türü adı. |
| Eleman | Etiket adı. |
| EntityReference | Referans verilen varlığın adı. |
| ProcessingInstruction | İşleme talimatının hedefi. |
| XmlDeclaration | Düz dize xml. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
