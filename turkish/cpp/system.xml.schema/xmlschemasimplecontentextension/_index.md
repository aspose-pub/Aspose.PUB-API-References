---
title: "System::Xml::Schema::XmlSchemaSimpleContentExtension sınıfı"
linktitle: "XmlSchemaSimpleContentExtension"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentExtension sınıfı. XML Şema'dan basit içerik için uzantı öğesini temsil eder ve World Wide Web Konsorsiyumu (W3C) tarafından belirtilmiştir. Bu sınıf, basit tipleri uzantı yoluyla türetmek için kullanılabilir. Bu tür türetmeler, öğenin basit tip içeriğini C++'ta öznitelikler ekleyerek genişletmek için kullanılır."
type: docs
weight: 6000
url: /tr/cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Basit içerik için XML [Şema](../) üzerinden **extension** öğesini temsil eder ve World Wide Web Konsorsiyumu (W3C) tarafından belirtilmiştir. Bu sınıf, uzantı yoluyla basit tipleri türetmek için kullanılabilir. Bu tür türetmeler, öğenin basit tip içeriğini öznitelikler ekleyerek genişletmek için kullanılır.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Öznitelik değeri için kullanılacak [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) döndürür. |
| [get_Attributes](./get_attributes/)() | [XmlSchemaAttribute](../xmlschemaattribute/) ve [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) koleksiyonunu döndürür. |
| [get_BaseTypeName](./get_basetypename/)() | Bu tipin uzatıldığı yerleşik veri tipi veya basit tipin adını döndürür. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Öznitelik değeri için kullanılacak [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ayarlar. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu tipin uzatıldığı yerleşik veri tipi veya basit tipin adını ayarlar. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | [XmlSchemaSimpleContentExtension](./) sınıfının yeni bir örneğini başlatır. |
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
