---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateAttribute yöntemi"
linktitle: "ValidateAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateAttribute yöntemi. C++'ta geçerli öğe bağlamında öznitelik adını, ad alanı URI'sini ve değerini doğrular."
type: docs
weight: 1600
url: /tr/cpp/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const String\& | Doğrulanacak öznitelik için yerel ad. |
| namespaceUri | const String\& | Doğrulanacak öznitelik için ad alanı URI'si. |
| attributeValue | const String\& | Doğrulanacak öznitelik değeri. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Özniteliğin başarılı doğrulamasının ardından özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |

### ReturnValue

Doğrulanan öznitelik değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const String\& | Doğrulanacak öznitelik için yerel ad. |
| namespaceUri | const String\& | Doğrulanacak öznitelik için ad alanı URI'si. |
| attributeValue | XmlValueGetter | Özniteliğin değerini, özniteliğin XML [Schema](../../) Tanım Dili (XSD) türüyle uyumlu bir tip olarak iletmek için kullanılan bir XmlValueGetter geri çağrısı. |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | Özniteliğin başarılı doğrulamasının ardından özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |

### ReturnValue

Doğrulanan öznitelik değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
