---
title: "System::Xml::XmlDocument::CreateDocumentType Methode"
linktitle: "CreateDocumentType"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlDocument::CreateDocumentType Methode. Gibt ein neues XmlDocumentType-Objekt in C++ zurück."
type: docs
weight: 700
url: /de/cpp/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType method


Gibt ein neues [XmlDocumentType](../../xmldocumenttype/) Objekt zurück.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | const String\& | Name des Dokumenttyps. |
| publicId | const String\& | Der öffentliche Bezeichner des Dokumenttyps oder **nullptr**. Sie können eine öffentliche URI und auch einen Systembezeichner angeben, um den Ort des externen DTD-Teils zu identifizieren. |
| systemId | const String\& | Der Systembezeichner des Dokumenttyps oder **nullptr**. Gibt die URL des Dateipfads für das externe DTD-Teil an. |
| internalSubset | const String\& | Der interne DTD-Teil des Dokumenttyps oder **nullptr**. |

### ReturnValue

Das neue [XmlDocumentType](../../xmldocumenttype/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
