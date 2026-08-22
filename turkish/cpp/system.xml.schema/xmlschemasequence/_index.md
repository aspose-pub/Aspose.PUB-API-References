---
title: "System::Xml::Schema::XmlSchemaSequence class"
linktitle: "XmlSchemaSequence"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSequence class. XML Şemasından, World Wide Web Consortium (W3C) tarafından belirtilen sıralama öğesini (kompozitör) temsil eder. Sıralama, gruptaki öğelerin C++'da içinde bulunduran öğe içinde belirtilen sırada görünmesini gerektirir."
type: docs
weight: 5700
url: /tr/cpp/system.xml.schema/xmlschemasequence/
---
## XmlSchemaSequence class


XML [Schema](../) içindeki **sequence** öğesini (kompozitör) World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. **sequence** gruptaki öğelerin içinde bulunduran öğe içinde belirtilen sırada görünmesini gerektirir.

```cpp
class XmlSchemaSequence : public System::Xml::Schema::XmlSchemaGroupBase
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Items](./get_items/)() override | Bileştirici içinde bulunan öğeler. [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaSequence](./) veya [XmlSchemaAny](../xmlschemaany/) koleksiyonu. |
| [XmlSchemaSequence](./xmlschemasequence/)() | [XmlSchemaSequence](./) sınıfının yeni bir örneğini başlatır. |
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
