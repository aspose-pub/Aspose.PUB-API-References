---
title: "System::Xml::Schema::XmlSchemaAttributeGroup sınıfı"
linktitle: "XmlSchemaAttributeGroup"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAttributeGroup sınıfı. XML Şeması'ndan attributeGroup öğesini, World Wide Web Consortium (W3C) tarafından belirtildiği gibi temsil eder. AttributesGroups, bir dizi attribute bildiriminin bir grup olarak birleştirilip C++'da karmaşık tip tanımlarına dahil edilmesini sağlayan bir mekanizma sunar."
type: docs
weight: 1200
url: /tr/cpp/system.xml.schema/xmlschemaattributegroup/
---
## XmlSchemaAttributeGroup class


XML [Schema](../) üzerinden **attributeGroup** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. AttributesGroups, bir dizi attribute bildirimini bir grup olarak birleştirip karmaşık tip tanımlarına dahil edilmesini sağlayan bir mekanizma sunar.

```cpp
class XmlSchemaAttributeGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Öznitelik grubunun [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşenini döndürür. |
| [get_Attributes](./get_attributes/)() | Öznitelik grubunun öznitelik koleksiyonunu döndürür. [XmlSchemaAttribute](../xmlschemaattribute/) ve [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) öğelerini içerir. |
| [get_Name](./get_name/)() | Öznitelik grubunun adını döndürür. |
| [get_QualifiedName](./get_qualifiedname/)() | Öznitelik grubunun nitelikli adını döndürür. |
| [get_RedefinedAttributeGroup](./get_redefinedattributegroup/)() | XML [Schema](../) üzerinden yeniden tanımlanmış öznitelik grubu özelliğini döndürür. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Öznitelik grubunun [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşenini ayarlar. |
| [set_Name](./set_name/)(const String\&) | Öznitelik grubunun adını ayarlar. |
| [XmlSchemaAttributeGroup](./xmlschemaattributegroup/)() | Yeni bir [XmlSchemaAttributeGroup](./) sınıf örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
