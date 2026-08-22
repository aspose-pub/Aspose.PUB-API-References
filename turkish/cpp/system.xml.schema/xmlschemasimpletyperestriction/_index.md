---
title: "System::Xml::Schema::XmlSchemaSimpleTypeRestriction sınıfı"
linktitle: "XmlSchemaSimpleTypeRestriction"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleTypeRestriction sınıfı. XML Şeması'ndan basit tipler için **restriction** öğesini, World Wide Web Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, C++'ta simpleType öğesini kısıtlamak için kullanılabilir."
type: docs
weight: 6500
url: /tr/cpp/system.xml.schema/xmlschemasimpletyperestriction/
---
## XmlSchemaSimpleTypeRestriction class


XML [Schema](../) üzerinden **restriction** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, **simpleType** öğesini kısıtlamak için kullanılabilir.

```cpp
class XmlSchemaSimpleTypeRestriction : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_BaseType](./get_basetype/)() | Temel tip hakkında bilgi döndürür. |
| [get_BaseTypeName](./get_basetypename/)() | Nitelikli temel tipin adını döndürür. |
| [get_Facets](./get_facets/)() | Bir [Xml](../../system.xml/)[Schema](../) özelliğini döndürür. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Temel tip hakkında bilgi ayarlar. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Nitelikli temel tipin adını ayarlar. |
| [XmlSchemaSimpleTypeRestriction](./xmlschemasimpletyperestriction/)() | Yeni bir [XmlSchemaSimpleTypeRestriction](./) sınıfı örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
