---
title: "System::Xml::Schema::XmlSchemaAttributeGroupRef sınıfı"
linktitle: "XmlSchemaAttributeGroupRef"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAttributeGroupRef sınıfı. XML Şeması'ndan ref özniteliğiyle attributeGroup öğesini temsil eder. AttributesGroupRef, bir attributeGroup için referanstır; name özelliği C++'da referans verilen attribute group'u içerir."
type: docs
weight: 1300
url: /tr/cpp/system.xml.schema/xmlschemaattributegroupref/
---
## XmlSchemaAttributeGroupRef class


XML [Schema](../) üzerinden **ref** özniteliğiyle **attributeGroup** öğesini temsil eder, [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454) tarafından belirtildiği gibi. AttributesGroupRef, bir attributeGroup için referanstır; name özelliği referans verilen attribute group'u içerir.

```cpp
class XmlSchemaAttributeGroupRef : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_RefName](./get_refname/)() | Referans verilen **attributeGroup** öğesinin adını döndürür. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Referans verilen **attributeGroup** öğesinin adını ayarlar. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/)() | [XmlSchemaAttributeGroupRef](./) sınıfının yeni bir örneğini başlatır. |
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
