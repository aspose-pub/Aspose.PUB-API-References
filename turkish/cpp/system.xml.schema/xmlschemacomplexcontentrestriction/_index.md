---
title: "System::Xml::Schema::XmlSchemaComplexContentRestriction sınıfı"
linktitle: "XmlSchemaComplexContentRestriction"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaComplexContentRestriction sınıfı. XML Şeması'ndan (XML Schema) World Wide Web Consortium (W3C) tarafından belirlenen restriction öğesini temsil eder. Bu sınıf, kısıtlama yoluyla türetilen karmaşık içerik modeline sahip karmaşık tipler içindir. Karmaşık tipin içeriğini, C++'da kalıtılan karmaşık tipin bir alt kümesine kısıtlar."
type: docs
weight: 2000
url: /tr/cpp/system.xml.schema/xmlschemacomplexcontentrestriction/
---
## XmlSchemaComplexContentRestriction class


XML [Schema](../) üzerinden World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirlenen **restriction** öğesini temsil eder. Bu sınıf, kısıtlama yoluyla türetilen karmaşık içerik modeline sahip karmaşık tipler içindir. Karmaşık tipin içeriğini, kalıtılan karmaşık tipin bir alt kümesine kısıtlar.

```cpp
class XmlSchemaComplexContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Karmaşık içerik modelinin [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşenini döndürür. |
| [get_Attributes](./get_attributes/)() | Karmaşık tip için öznitelik koleksiyonunu döndürür. [XmlSchemaAttribute](../xmlschemaattribute/) ve [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) öğelerini içerir. |
| [get_BaseTypeName](./get_basetypename/)() | Bu tipin kısıtlama yoluyla türetildiği karmaşık tipin adını döndürür. |
| [get_Particle](./get_particle/)() | [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından birini döndürür. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Karmaşık içerik modelinin [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşenini ayarlar. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu tipin kısıtlama yoluyla türetildiği karmaşık tipin adını ayarlar. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından birini ayarlar. |
| [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/)() | [XmlSchemaComplexContentRestriction](./) sınıfının yeni bir örneğini başlatır. |
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
