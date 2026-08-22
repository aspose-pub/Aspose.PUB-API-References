---
title: "System::Xml::Schema::XmlSchemaSet::Add metodu"
linktitle: "Ekle"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSet::Add metodu. Verilen XmlSchema'yi C++'ta XmlSchemaSet'e ekler."
type: docs
weight: 200
url: /tr/cpp/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Verilen [XmlSchema](../../xmlschema/) öğesini [XmlSchemaSet](../) öğesine ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const SharedPtr\<XmlSchema\>\& | Eklenecek [XmlSchema](../../xmlschema/) nesnesi [XmlSchemaSet](../) öğesine. |

### ReturnValue

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değilse ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Verilen [XmlSchemaSet](../) içindeki tüm XML [Schema](../../) tanım dili (XSD) şemalarını [XmlSchemaSet](../) öğesine ekler.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | [XmlSchemaSet](../) nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


XML [Schema](../../) tanım dili (XSD) şemasını [XmlReader](../../../system.xml/xmlreader/) içinde bulunan [XmlSchemaSet](../) öğesine ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | String | Şemanın **targetNamespace** değeri, ya da şemada belirtilen **targetNamespace** değerini kullanmak için **nullptr**. |
| schemaDocument | const SharedPtr\<XmlReader\>\& | [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

### ReturnValue

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değilse ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaSet::Add(String, const String\&) method


Belirtilen URL'deki XML [Schema](../../) tanım dili (XSD) şemasını [XmlSchemaSet](../) öğesine ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | String | Şemanın **targetNamespace** değeri, ya da şemada belirtilen **targetNamespace** değerini kullanmak için **nullptr**. |
| schemaUri | const String\& | Yüklemek için şemayı belirten URL. |

### ReturnValue

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değilse ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
