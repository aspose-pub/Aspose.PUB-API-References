---
title: "System::Xml::Schema::XmlSchemaDatatype::ChangeType yöntemi"
linktitle: "ChangeType"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaDatatype::ChangeType yöntemi. Belirtilen değeri, tipi XmlSchemaDatatype tarafından temsil edilen XML şema tipinin geçerli temsillerinden biri olan, C++'ta belirtilen çalışma zamanı tipine dönüştürür."
type: docs
weight: 100
url: /tr/cpp/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Belirtilen değeri, tipi [XmlSchemaDatatype](../) tarafından temsil edilen XML şema tipinin geçerli temsillerinden biri olan, belirtilen çalışma zamanı tipine dönüştürür.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | SharedPtr\<Object\> | Belirtilen türe dönüştürülecek giriş değeri. |
| targetType | const TypeInfo\& | Giriş değerinin dönüştürüleceği hedef tür. |

### ReturnValue

Dönüştürülmüş giriş değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Belirtilen değeri, türü [XmlSchemaDatatype](../) tarafından temsil edilen XML şema türünün geçerli temsillerinden biri ise, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) kullanılarak belirtilen çalışma zamanı türüne dönüştürür; bu, [XmlSchemaDatatype](../) **xs:QName** türünü veya ondan türetilmiş bir türü temsil ediyorsa geçerlidir.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | SharedPtr\<Object\> | Belirtilen türe dönüştürülecek giriş değeri. |
| targetType | const TypeInfo\& | Giriş değerinin dönüştürüleceği hedef tür. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Namespace öneklerini çözmek için kullanılan bir [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/). Bu, yalnızca [XmlSchemaDatatype](../) **xs:QName** türünü veya ondan türetilmiş bir türü temsil ediyorsa kullanışlıdır. |

### ReturnValue

Dönüştürülmüş giriş değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
