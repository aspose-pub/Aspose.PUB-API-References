---
title: "System::Xml::Schema::XmlSchemaGroupRef sınıfı"
linktitle: "XmlSchemaGroupRef"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaGroupRef sınıfı. XML Şeması'ndan ref özniteliğine sahip grup öğesini World Wide Web Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, C++'da şema seviyesinde tanımlı bir gruba başvuran karmaşık tipler içinde kullanılır."
type: docs
weight: 3300
url: /tr/cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


XML [Schema](../) üzerinden **ref** özniteliğine sahip **group** öğesini World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, **schema** seviyesinde tanımlı bir **group**'a başvuran karmaşık tipler içinde kullanılır.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Particle](./get_particle/)() | Post-derleme yorumunu **Particle** değerinin tutan [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından birini döndürür. |
| [get_RefName](./get_refname/)() | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) tanımlı bir grupun adını döndürür. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) tanımlı bir grupun adını ayarlar. |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Yeni bir [XmlSchemaGroupRef](./) sınıf örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
