---
title: "System::Xml::Schema::XmlSchemaSimpleType sınıfı"
linktitle: "XmlSchemaSimpleType"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleType sınıfı. XML Şema üzerinden basit içerik için **simpleType** öğesini Dünya Çapında Web Konsorsiyumu (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf basit bir tür tanımlar. Basit türler, C++'ta yalnızca metin içeren özniteliklerin veya öğelerin değerleri için bilgi ve kısıtlamalar belirtebilir."
type: docs
weight: 6200
url: /tr/cpp/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType class


XML [Şema](../) üzerinden basit içerik için **simpleType** öğesini Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf basit bir tür tanımlar. Basit türler, yalnızca metin içeren özniteliklerin veya öğelerin değerleri için bilgi ve kısıtlamalar belirtebilir.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Content](./get_content/)() | [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) veya [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) öğelerinden birini döndürür. |
| [set_Content](./set_content/)(const SharedPtr\<XmlSchemaSimpleTypeContent\>\&) | [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) veya [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) öğelerinden birini ayarlar. |
| [XmlSchemaSimpleType](./xmlschemasimpletype/)() | [XmlSchemaSimpleType](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
