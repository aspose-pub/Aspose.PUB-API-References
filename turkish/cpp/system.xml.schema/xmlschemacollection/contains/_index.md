---
title: "System::Xml::Schema::XmlSchemaCollection::Contains metodu"
linktitle: "Contains"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaCollection::Contains yöntemi. Belirtilen XmlSchema'nin targetNamespace'inin koleksiyonda olup olmadığını gösteren bir değer döndürür C++ içinde."
type: docs
weight: 300
url: /tr/cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Belirtilen [XmlSchema](../../xmlschema/)nin **targetNamespace**'inin koleksiyonda olup olmadığını gösteren bir değer döndürür.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | [XmlSchema](../../xmlschema/) nesnesi. |

### ReturnValue

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaCollection::Contains(const String\&) method


Belirtilen ad alanına sahip bir şemanın koleksiyonda olup olmadığını gösteren bir değer döndürür.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ns | const String\& | Şema ile ilişkili namespace URI'si. XML Şemaları için, genellikle hedef ad alanı olur. |

### ReturnValue

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
