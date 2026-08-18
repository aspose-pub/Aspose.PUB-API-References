---
title: "System::Xml::Schema::XmlSchemaDatatype::ParseValue Methode"
linktitle: "ParseValue"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaDatatype::ParseValue-Methode. Wenn sie in einer abgeleiteten Klasse überschrieben wird, validiert sie die angegebene Zeichenkette gegen einen integrierten oder benutzerdefinierten einfachen Typ in C++."
type: docs
weight: 700
url: /de/cpp/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue method


Wird in einer abgeleiteten Klasse überschrieben, validiert den angegebenen **string** gegen einen integrierten oder benutzerdefinierten einfachen Typ.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Die **string** zum Validieren gegen den einfachen Typ. |
| nameTable | SharedPtr\<XmlNameTable\> | Die [XmlNameTable](../../../system.xml/xmlnametable/) zu verwenden für die Atomisierung beim Parsen der **string**, falls dieses [XmlSchemaDatatype](../)-Objekt den **xs:NCName**-Typ darstellt. |
| nsmgr | SharedPtr\<IXmlNamespaceResolver\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt zu verwenden beim Parsen der **string**, falls dieses [XmlSchemaDatatype](../)-Objekt den **xs:QName**-Typ darstellt. |

### ReturnValue

Ein [Object](../../../system/object/), das sicher in den von dem Aufruf [XmlSchemaDatatype::get_ValueType](../get_valuetype/) zurückgegebenen Typ umgewandelt werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
