---
title: "System::Xml::Schema::XmlSchemaGroup sınıfı"
linktitle: "XmlSchemaGroup"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaGroup sınıfı. XML Şeması'ndan (XML Schema) World Wide Web Consortium (W3C) tarafından belirlenen grup öğesini temsil eder. Bu sınıf, karmaşık tiplerden referans verilen şema seviyesindeki grupları tanımlar. Eleman bildirimlerinin bir kümesini gruplar, böylece C++'da karmaşık tip tanımlarına grup olarak dahil edilebilir."
type: docs
weight: 3100
url: /tr/cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


XML [Schema](../) üzerinden World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirlenen **group** öğesini temsil eder. Bu sınıf, karmaşık tiplerden referans verilen **schema** seviyesindeki grupları tanımlar. Eleman bildirimlerinin bir kümesini gruplar, böylece karmaşık tip tanımlarına grup olarak dahil edilebilir.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Name](./get_name/)() | Şema grubunun adını döndürür. |
| [get_Particle](./get_particle/)() | [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından birini döndürür. |
| [get_QualifiedName](./get_qualifiedname/)() | Şema grubunun nitelikli adını döndürür. |
| [set_Name](./set_name/)(const String\&) | Şema grubunun adını ayarlar. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından birini ayarlar. |
| [XmlSchemaGroup](./xmlschemagroup/)() | [XmlSchemaGroup](./) sınıfının yeni bir örneğini başlatır. |
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
