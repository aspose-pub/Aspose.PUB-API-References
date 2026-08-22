---
title: "System::Xml::Schema::XmlSchemaSet::Contains yöntemi"
linktitle: "Contains"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSet::Contains yöntemi. Belirtilen XML Schema tanım dili (XSD) XmlSchema nesnesinin C++'ta XmlSchemaSet içinde olup olmadığını gösterir."
type: docs
weight: 400
url: /tr/cpp/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) method


Belirtilen XML [Schema](../../) tanım dili (XSD) [XmlSchema](../../xmlschema/) nesnesinin [XmlSchemaSet](../) içinde olup olmadığını gösterir.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | [XmlSchema](../../xmlschema/) nesnesi. |

### ReturnValue

**true** if the [XmlSchema](../../xmlschema/) object is in the [XmlSchemaSet](../); otherwise, **false**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaSet::Contains(String) method


Belirtilen hedef ad alanı URI'sine sahip bir XML [Schema](../../) tanım dili (XSD) şemasının [XmlSchemaSet](../) içinde olup olmadığını gösterir.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | String | Şemanın **targetNamespace** özelliği. |

### ReturnValue

**true** if a schema with the specified target namespace URI is in the [XmlSchemaSet](../); otherwise, **false**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
