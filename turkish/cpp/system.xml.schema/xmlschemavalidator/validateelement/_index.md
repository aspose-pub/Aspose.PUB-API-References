---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateElement method"
linktitle: "ValidateElement"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateElement yöntemi. Geçerli bağlamda öğeyi doğrular C++ içinde."
type: docs
weight: 1700
url: /tr/cpp/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Geçerli bağlamda öğeyi doğrular.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const String\& | Doğrulanacak öğenin yerel adı. |
| namespaceUri | const String\& | Doğrulanacak öğenin ad alanı URI'si. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Öğenin adının başarılı doğrulaması üzerine özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method


Belirtilen **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** ve **xsi:NoNamespaceSchemaLocation** öznitelik değerleriyle geçerli bağlamda öğeyi doğrular.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const String\& | Doğrulanacak öğenin yerel adı. |
| namespaceUri | const String\& | Doğrulanacak öğenin ad alanı URI'si. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Öğenin adının başarılı doğrulaması üzerine özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |
| xsiType | const String\& | Öğenin **xsi:Type** öznitelik değeri. Bu parametre **nullptr** olabilir. |
| xsiNil | const String\& | Öğenin **xsi:Nil** öznitelik değeri. Bu parametre **nullptr** olabilir. |
| xsiSchemaLocation | const String\& | Bu **xsi:SchemaLocation** özniteliğinin değeri. Bu parametre **nullptr** olabilir. |
| xsiNoNamespaceSchemaLocation | const String\& | Bu **xsi:NoNamespaceSchemaLocation** özniteliğinin değeri. Bu parametre **nullptr** olabilir. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
