---
title: "System::Xml::Schema::XmlSchemaChoice class"
linktitle: "XmlSchemaChoice"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaChoice sınıfı. Dünya Çapında Ağ Konsorsiyumu (W3C) tarafından belirlenen XML Şemasından seçim öğesini (kompozitörü) temsil eder. Seçim, C++'da bir örnekte yalnızca bir çocuğunun görünmesine izin verir."
type: docs
weight: 1400
url: /tr/cpp/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice class


XML [Schema](../) öğesinden **choice** (kompozitör) öğesini Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirtildiği gibi temsil eder. **choice**, bir örnekte yalnızca bir çocuğunun görünmesine izin verir.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Items](./get_items/)() override | Kompozitör (**choice**) ile içerilen öğelerin koleksiyonunu döndürür: [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/), veya [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaChoice](./xmlschemachoice/)() | Yeni bir [XmlSchemaChoice](./) sınıfı örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaGroupBase](../xmlschemagroupbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
