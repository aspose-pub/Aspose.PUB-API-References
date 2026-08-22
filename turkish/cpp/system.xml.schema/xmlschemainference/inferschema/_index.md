---
title: "System::Xml::Schema::XmlSchemaInference::InferSchema metodu"
linktitle: "InferSchema"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaInference::InferSchema metodu. C++'ta belirtilen XmlReader nesnesinde bulunan XML belgesinden bir XML Şema Tanım Dili (XSD) şeması türetir."
type: docs
weight: 400
url: /tr/cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden bir XML [Schema](../../) Tanım Dili (XSD) şeması türetir.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Şema türetmek için XML belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

### ReturnValue

Türetilen şemaları içeren bir [XmlSchemaSet](../../xmlschemaset/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden bir XML [Schema](../../) Tanım Dili (XSD) şeması türetir ve aynı hedef ad alanına sahip [XmlSchemaSet](../../xmlschemaset/) nesnesinde bulunan mevcut bir şemayı kullanarak türetilen şemayı iyileştirir.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instanceDocument | const SharedPtr\<XmlReader\>\& | Şema türetmek için XML belgesini içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |
| schemas | SharedPtr\<XmlSchemaSet\> | Türetilen şemayı iyileştirmek için kullanılan mevcut bir şemayı içeren bir [XmlSchemaSet](../../xmlschemaset/) nesnesi. |

### ReturnValue

Türetilen şemaları içeren bir [XmlSchemaSet](../../xmlschemaset/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
