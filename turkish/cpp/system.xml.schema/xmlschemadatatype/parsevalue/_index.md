---
title: "System::Xml::Schema::XmlSchemaDatatype::ParseValue method"
linktitle: "ParseValue"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaDatatype::ParseValue yöntemi. Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyi C++'da yerleşik veya kullanıcı tanımlı basit bir türe karşı doğrular."
type: docs
weight: 700
url: /tr/cpp/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue method


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen **string** değerini yerleşik veya kullanıcı tanımlı bir basit tipe karşı doğrular.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | String | Basit türe karşı doğrulanacak **string**. |
| nameTable | SharedPtr\<XmlNameTable\> | Bu [XmlSchemaDatatype](../) nesnesi **xs:NCName** türünü temsil ediyorsa, **string**'i ayrıştırırken atomizasyon için kullanılacak [XmlNameTable](../../../system.xml/xmlnametable/). |
| nsmgr | SharedPtr\<IXmlNamespaceResolver\> | Bu [XmlSchemaDatatype](../) nesnesi **xs:QName** türünü temsil ediyorsa, **string**'i ayrıştırırken kullanılacak [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

Bir [Object](../../../system/object/) nesnesi, [XmlSchemaDatatype::get_ValueType](../get_valuetype/) çağrısı tarafından döndürülen türe güvenli bir şekilde dönüştürülebilir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
