---
title: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement yöntemi"
linktitle: "ValidateEndElement"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaValidator::ValidateEndElement yöntemi. Basit içeriğe sahip öğeler için öğenin metin içeriğinin veri tipine göre geçerli olup olmadığını doğrular ve karmaşık içeriğe sahip öğeler için geçerli öğenin içeriğinin tamamlanmış olup olmadığını C++'ta doğrular."
type: docs
weight: 1800
url: /tr/cpp/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


Basit içerikli öğeler için öğenin metin içeriğinin veri türüne göre geçerli olup olmadığını ve karmaşık içerikli öğeler için geçerli öğenin içeriğinin tamam olup olmadığını doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin başarılı doğrulaması sırasında özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |

### ReturnValue

Öğe basit içeriğe sahipse ayrıştırılmış, tiplenmiş metin değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


Belirtilen öğenin metin içeriğinin veri türüne göre geçerli olup olmadığını doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemaInfo | const SharedPtr\<XmlSchemaInfo\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin metin içeriğinin başarılı doğrulaması sırasında özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |
| typedValue | const SharedPtr\<Object\>\& | Öğenin tiplenmiş metin içeriği. |

### ReturnValue

Öğenin ayrıştırılmış, tiplenmiş basit içeriği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
