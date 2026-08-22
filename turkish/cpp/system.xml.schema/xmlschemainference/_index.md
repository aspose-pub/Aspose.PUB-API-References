---
title: "System::Xml::Schema::XmlSchemaInference sınıfı"
linktitle: "XmlSchemaInference"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaInference sınıfı. Bir XML belgesinden XML Şema Tanım Dili (XSD) şeması çıkarır. XmlSchemaInference sınıfı C++'ta kalıtılamaz."
type: docs
weight: 3700
url: /tr/cpp/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference class


Bir XML belgesinden XML [Schema](../) Tanım Dili (XSD) şeması çıkarır. [XmlSchemaInference](./) sınıfı kalıtılamaz.

```cpp
class XmlSchemaInference : public System::Object
```

## Enums

| Enum | Açıklama |
| --- | --- |
| [InferenceOption](./inferenceoption/) | [XmlSchemaInference](./) sınıfı tarafından bir XML belgesindeki öğeler ve öznitelikler için çıkarılan oluş ve tip bilgilerini etkiler. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Occurrence](./get_occurrence/)() | XML belgesinden çıkarılan şema oluş bildirimlerini etkileyen [XmlSchemaInference::InferenceOption](./inferenceoption/) değerini döndürür. |
| [get_TypeInference](./get_typeinference/)() | XML belgesinden çıkarılan tipleri etkileyen [XmlSchemaInference::InferenceOption](./inferenceoption/) değerini döndürür. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden XML [Schema](../) Tanım Dili (XSD) şeması çıkarır. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinde bulunan XML belgesinden XML [Schema](../) Tanım Dili (XSD) şeması çıkarır ve aynı hedef ad alanına sahip belirtilen [XmlSchemaSet](../xmlschemaset/) nesnesindeki mevcut şemayı kullanarak çıkarılan şemayı iyileştirir. |
| [set_Occurrence](./set_occurrence/)(XmlSchemaInference::InferenceOption) | XML belgesinden çıkarılan şema oluş bildirimlerini etkileyen [XmlSchemaInference::InferenceOption](./inferenceoption/) değerini ayarlar. |
| [set_TypeInference](./set_typeinference/)(XmlSchemaInference::InferenceOption) | XML belgesinden çıkarılan tipleri etkileyen [XmlSchemaInference::InferenceOption](./inferenceoption/) değerini ayarlar. |
| [XmlSchemaInference](./xmlschemainference/)() | [XmlSchemaInference](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
