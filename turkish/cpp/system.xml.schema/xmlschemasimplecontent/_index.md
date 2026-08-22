---
title: "System::Xml::Schema::XmlSchemaSimpleContent sınıfı"
linktitle: "XmlSchemaSimpleContent"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleContent sınıfı. World Wide Web Consortium (W3C) tarafından belirlenen XML Schema'dan simpleContent öğesini temsil eder. Bu sınıf, C++'ta basit içerik modeline sahip basit ve karmaşık tipler içindir."
type: docs
weight: 5900
url: /tr/cpp/system.xml.schema/xmlschemasimplecontent/
---
## XmlSchemaSimpleContent class


XML [Schema](../) tarafından belirlenen **simpleContent** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından tanımlanmış olarak temsil eder. Bu sınıf, basit içerik modeline sahip basit ve karmaşık tipler içindir.

```cpp
class XmlSchemaSimpleContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Content](./get_content/)() override | Aşağıdakilerden birini döndürür: [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) veya [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Aşağıdakilerden birini döndürür: [XmlSchemaSimpleContentRestriction](../xmlschemasimplecontentrestriction/) veya [XmlSchemaSimpleContentExtension](../xmlschemasimplecontentextension/). |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
