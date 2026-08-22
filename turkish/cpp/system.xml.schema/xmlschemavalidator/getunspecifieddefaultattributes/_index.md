---
title: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes method"
linktitle: "GetUnspecifiedDefaultAttributes"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes yöntemi. Varsayılan öznitelikler üzerindeki kimlik kısıtlamalarını doğrular ve C++'da öğe bağlamında XmlSchemaValidator::ValidateAttribute yöntemiyle daha önce doğrulanmamış varsayılan değere sahip öznitelikler için belirtilen List'i XmlSchemaAttribute nesneleriyle doldurur."
type: docs
weight: 900
url: /tr/cpp/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes method


Varsayılan öznitelikler üzerindeki kimlik kısıtlamalarını doğrular ve öğe bağlamında [XmlSchemaValidator::ValidateAttribute](../validateattribute/) yöntemini daha önce kullanmamış varsayılan değere sahip öznitelikler için belirtilen List'i [XmlSchemaAttribute](../../xmlschemaattribute/) nesneleriyle doldurur.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| defaultAttributes | const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\& | Öğe bağlamında doğrulama sırasında henüz karşılaşılmamış öznitelikler için [XmlSchemaAttribute](../../xmlschemaattribute/) nesneleriyle doldurulacak bir List. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
