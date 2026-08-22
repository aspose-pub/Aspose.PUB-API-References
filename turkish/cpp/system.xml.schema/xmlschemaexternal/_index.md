---
title: "System::Xml::Schema::XmlSchemaExternal sınıfı"
linktitle: "XmlSchemaExternal"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaExternal sınıfı. C++'ta dahil edilen şema hakkında bilgi sağlar."
type: docs
weight: 2800
url: /tr/cpp/system.xml.schema/xmlschemaexternal/
---
## XmlSchemaExternal class


Dahil edilen şema hakkında bilgi sağlar.

```cpp
class XmlSchemaExternal : public System::Xml::Schema::XmlSchemaObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Id](./get_id/)() | Dize kimliğini döndürür. |
| [get_Schema](./get_schema/)() | Referans verilen şema için [XmlSchema](../xmlschema/) öğesini döndürür. |
| [get_SchemaLocation](./get_schemalocation/)() | Şema için Birleşik Kaynak Tanımlayıcısı (URI) konumunu döndürür; bu, şema işlemcisine şemanın fiziksel olarak nerede bulunduğunu bildirir. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Şema hedef ad alanına ait olmayan nitelikli öznitelikleri döndürür. |
| [set_Id](./set_id/)(const String\&) | Dize kimliğini ayarlar. |
| [set_Schema](./set_schema/)(const SharedPtr\<XmlSchema\>\&) | Referans verilen şema için [XmlSchema](../xmlschema/) öğesini ayarlar. |
| [set_SchemaLocation](./set_schemalocation/)(const String\&) | Şema için Birleşik Kaynak Tanımlayıcısı (URI) konumunu ayarlar; bu, şema işlemcisine şemanın fiziksel olarak nerede bulunduğunu bildirir. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Şema hedef ad alanına ait olmayan nitelikli öznitelikleri ayarlar. |
| [XmlSchemaExternal](./xmlschemaexternal/)() | [XmlSchemaExternal](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
