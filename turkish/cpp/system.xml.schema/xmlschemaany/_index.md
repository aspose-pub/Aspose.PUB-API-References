---
title: "System::Xml::Schema::XmlSchemaAny sınıfı"
linktitle: "XmlSchemaAny"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAny sınıfı. World Wide Web Consortium (W3C) tarafından tanımlanan **any** öğesini C++'ta temsil eder."
type: docs
weight: 800
url: /tr/cpp/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny class


World Wide [Web](../../system.web/) Consortium (W3C) **any** öğesini temsil eder.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Kullanılabilecek öğeleri içeren ad alanlarını döndürür. |
| [get_ProcessContents](./get_processcontents/)() | **any** öğesiyle belirtilen öğeler için XML belgelerinin doğrulamasının bir uygulama veya XML işlemcisi tarafından nasıl ele alınması gerektiği hakkında bilgi döndürür. |
| [set_Namespace](./set_namespace/)(const String\&) | Kullanılabilecek öğeleri içeren ad alanlarını ayarlar. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | **any** öğesiyle belirtilen öğeler için XML belgelerinin doğrulamasının bir uygulama veya XML işlemcisi tarafından nasıl ele alınması gerektiği hakkında bilgi ayarlar. |
| [XmlSchemaAny](./xmlschemaany/)() | Yeni bir [XmlSchemaAny](./) sınıfı örneği başlatır. |
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
