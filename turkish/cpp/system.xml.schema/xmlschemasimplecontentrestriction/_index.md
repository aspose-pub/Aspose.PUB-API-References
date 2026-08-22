---
title: "System::Xml::Schema::XmlSchemaSimpleContentRestriction sınıfı"
linktitle: "XmlSchemaSimpleContentRestriction"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentRestriction sınıfı. World Wide Web Consortium (W3C) tarafından belirtilen XML Schema'dan basit içerik için kısıtlama öğesini temsil eder. Bu sınıf, kısıtlama yoluyla basit tipler türetmek için kullanılabilir. Bu tür türetmeler, öğenin değer aralığını, C++ içinde kalıtılan basit tipte belirtilen değerlerin bir alt kümesine sınırlamak için kullanılabilir."
type: docs
weight: 6100
url: /tr/cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


XML [Schema](../) üzerinden basit içerik için **restriction** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, kısıtlama yoluyla basit tipler türetmek için kullanılabilir. Bu tür türetmeler, öğenin değer aralığını, kalıtılan basit tipte belirtilen değerlerin bir alt kümesine sınırlamak için kullanılabilir.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Özellik değeri için kullanılacak bir [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) döndürür. |
| [get_Attributes](./get_attributes/)() | Basit tip için [XmlSchemaAttribute](../xmlschemaattribute/) ve [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) öznitelik koleksiyonunu döndürür. |
| [get_BaseType](./get_basetype/)() | Basit tipin temel değerini döndürür. |
| [get_BaseTypeName](./get_basetypename/)() | Bu tipin türetildiği yerleşik veri tipi veya basit tipin adını döndürür. |
| [get_Facets](./get_facets/)() | Bir [Xml](../../system.xml/)[Schema](../) özelliğini döndürür. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Özellik değeri için kullanılacak bir [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ayarlar. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Basit tip temel değerini ayarlar. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu tipin türetildiği yerleşik veri tipi veya basit tipin adını ayarlar. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | [XmlSchemaSimpleContentRestriction](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
