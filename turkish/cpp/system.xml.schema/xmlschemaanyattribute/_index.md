---
title: "System::Xml::Schema::XmlSchemaAnyAttribute sınıfı"
linktitle: "XmlSchemaAnyAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAnyAttribute sınıfı. World Wide Web Consortium (W3C) anyAttribute öğesini C++'da temsil eder."
type: docs
weight: 900
url: /tr/cpp/system.xml.schema/xmlschemaanyattribute/
---
## XmlSchemaAnyAttribute class


World Wide [Web](../../system.web/) Consortium (W3C) **anyAttribute** öğesini temsil eder.

```cpp
class XmlSchemaAnyAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Kullanılabilecek öznitelikleri içeren ad alanlarını döndürür. |
| [get_ProcessContents](./get_processcontents/)() | **anyAttribute** öğesi tarafından belirtilen öznitelikler için XML belgelerinin doğrulamasının bir uygulama veya XML işlemcisi tarafından nasıl ele alınması gerektiği hakkında bilgi döndürür. |
| [set_Namespace](./set_namespace/)(const String\&) | Kullanılabilecek öznitelikleri içeren ad alanlarını ayarlar. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Bir uygulamanın veya XML işlemcisinin **anyAttribute** öğesiyle belirtilen öznitelikler için XML belgelerinin doğrulamasını nasıl ele alması gerektiği hakkında bilgi ayarlar. |
| [XmlSchemaAnyAttribute](./xmlschemaanyattribute/)() | Yeni bir [XmlSchemaAnyAttribute](./) sınıfı örneği başlatır. |
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
