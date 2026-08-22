---
title: "System::Xml::XmlTextReader::get_Value method"
linktitle: "get_Value"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::get_Value method. Geçerli düğümün metin değerini C++'ta döndürür."
type: docs
weight: 2900
url: /tr/cpp/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value method


Geçerli düğümün metin değerini döndürür.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### ReturnValue

Dönen değer, düğümün [XmlTextReader::get_NodeType](../get_nodetype/) değerine bağlıdır.
## Açıklamalar



Aşağıdaki tablo, döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm türleri [String::Empty](../../../system/string/empty/) döndürür. |||
|-|-|
| Düğüm Türü | Değer |
| Özellik | Özelliğin değeri. |
| CDATA | CDATA bölümünün içeriği. |
| Comment | Yorumun içeriği. |
| DocumentType | İç alt küme. |
| ProcessingInstruction | Hedef dışındaki tüm içerik. |
| SignificantWhitespace | xml:space='preserve' kapsamı içindeki boşluk. |
| Metin | Metin düğümünün içeriği. |
| Whitespace | İşaretleme arasındaki boşluk. |
| XmlDeclaration | Deklarasyonun içeriği. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
