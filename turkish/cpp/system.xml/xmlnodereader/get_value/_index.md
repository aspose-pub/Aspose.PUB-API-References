---
title: "System::Xml::XmlNodeReader::get_Value metodu"
linktitle: "get_Value"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNodeReader::get_Value metodu. C++'ta geçerli düğümün metin değerini döndürür."
type: docs
weight: 2100
url: /tr/cpp/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value method


Geçerli düğümün metin değerini döndürür.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### ReturnValue

Dönen değer, düğümün [XmlNodeReader::get_NodeType](../get_nodetype/) değerine bağlıdır.
## Açıklamalar



Aşağıdaki tablo, döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm türleri [String::Empty](../../../system/string/empty/) döndürür. |||
|-|-|
| Düğüm Türü | Değer |
| Özellik | Özelliğin değeri. |
| CDATA | CDATA bölümünün içeriği. |
| Comment | Yorumun içeriği. |
| DocumentType | İç alt küme. |
| ProcessingInstruction | Hedef dışındaki tüm içerik. |
| SignificantWhitespace | Karışık içerik modelinde işaretleme arasındaki boşluk. |
| Metin | Metin düğümünün içeriği. |
| Whitespace | İşaretleme arasındaki boşluk. |
| XmlDeclaration | Deklarasyonun içeriği. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
