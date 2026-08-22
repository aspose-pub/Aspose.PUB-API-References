---
title: "System::Xml::Schema::XmlSchemaSet::Reprocess yöntemi"
linktitle: "Yeniden İşleme"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSet::Reprocess yöntemi. C++'ta XmlSchemaSet içinde zaten mevcut olan bir XML Schema tanım dili (XSD) şemasını yeniden işler."
type: docs
weight: 1500
url: /tr/cpp/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess method


Zaten [XmlSchemaSet](../) içinde mevcut olan bir XML [Schema](../../) tanım dili (XSD) şemasını yeniden işler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| şema | SharedPtr\<XmlSchema\> | Yeniden işlenecek şema. |

### ReturnValue

Şema geçerli bir şema ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değilse ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde, bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
