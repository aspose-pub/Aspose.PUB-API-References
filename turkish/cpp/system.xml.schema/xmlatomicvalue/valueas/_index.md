---
title: "System::Xml::Schema::XmlAtomicValue::ValueAs yöntemi"
linktitle: "ValueAs"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlAtomicValue::ValueAs yöntemi. C++'da ad alanı öneklerini çözmek için belirtilen IXmlNamespaceResolver nesnesi kullanılarak belirtilen türe göre doğrulanan XML öğesi veya özniteliğinin değerini döndürür."
type: docs
weight: 1300
url: /tr/cpp/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs method


Doğrulanan XML öğesi veya özniteliğinin değerini, ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi kullanılarak belirtilen türe göre döndürür.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | const TypeInfo\& | Doğrulanan XML öğesi veya özniteliğinin değerini döndürülecek tür. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | Ad alanı öneklerini çözmek için kullanılan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |

### ReturnValue

Doğrulanan XML öğesi veya özniteliğinin değeri, istenen türde.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
