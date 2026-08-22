---
title: "System::Xml::Schema::XmlSchemaDatatype sınıfı"
linktitle: "XmlSchemaDatatype"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaDatatype sınıfı. XmlSchemaDatatype sınıfı, XML Schema tanım dili (XSD) tiplerini C++'ta çalışma zamanı tiplerine eşlemek için kullanılan soyut bir sınıftır."
type: docs
weight: 2400
url: /tr/cpp/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype class


[XmlSchemaDatatype](./) sınıfı, XML [Schema](../) tanım dili (XSD) tiplerini çalışma zamanı tiplerine eşlemek için kullanılan soyut bir sınıftır.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&) | Belirtilen değeri, türü [XmlSchemaDatatype](./) tarafından temsil edilen XML şema tipinin geçerli temsillerinden biri olan, belirtilen çalışma zamanı tipine dönüştürür. |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Belirtilen değeri, türü [XmlSchemaDatatype](./) tarafından temsil edilen XML şema tipinin geçerli temsillerinden biri olan, [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) kullanarak belirtilen çalışma zamanı tipine dönüştürür; eğer [XmlSchemaDatatype](./) **xs:QName** tipini veya ondan türetilmiş bir tipi temsil ediyorsa. |
| virtual [get_TokenizedType](./get_tokenizedtype/)() | Türetilmiş bir sınıfta geçersiz kılındığında, World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0 spesifikasyonunda belirtildiği gibi **string** tipini alır. |
| virtual [get_TypeCode](./get_typecode/)() | Basit tip için XmlTypeCode değerini döndürür. |
| virtual [get_ValueType](./get_valuetype/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin tipini alır. |
| virtual [get_Variety](./get_variety/)() | Basit tip için XmlSchemaDatatypeVariety değerini döndürür. |
| virtual [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaDatatype\>) | Bu yöntem her zaman **false** döndürür. |
| virtual [ParseValue](./parsevalue/)(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen **string** değerini yerleşik veya kullanıcı tanımlı bir basit tipe karşı doğrular. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
