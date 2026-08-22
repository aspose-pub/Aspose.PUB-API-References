---
title: "System::Xml::Schema::XmlSchemaImport sınıfı"
linktitle: "XmlSchemaImport"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaImport sınıfı. Dünya Çapında Ağ Konsorsiyumu (W3C) tarafından belirlenen XML Şemasından ithalat öğesini temsil eder. Bu sınıf, C++'ta diğer şemalardan şema bileşenlerini ithal etmek için kullanılır."
type: docs
weight: 3500
url: /tr/cpp/system.xml.schema/xmlschemaimport/
---
## XmlSchemaImport class


XML [Şema](../) üzerinden **import** öğesini temsil eder, Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirtildiği gibi. Bu sınıf, diğer şemalardan şema bileşenlerini içe aktarmak için kullanılır.

```cpp
class XmlSchemaImport : public System::Xml::Schema::XmlSchemaExternal
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Annotation](./get_annotation/)() | **annotation** değerini döndürür. |
| [get_Namespace](./get_namespace/)() | İçe aktarılan şema için hedef ad alanını Birleşik Kaynak Tanımlayıcısı (URI) referansı olarak döndürür. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | **annotation** değerini ayarlar. |
| [set_Namespace](./set_namespace/)(const String\&) | İçe aktarılan şema için hedef ad alanını Birleşik Kaynak Tanımlayıcısı (URI) referansı olarak ayarlar. |
| [XmlSchemaImport](./xmlschemaimport/)() | [XmlSchemaImport](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
