---
title: "System::Xml::Schema::XmlSchemaDocumentation sınıfı"
linktitle: "XmlSchemaDocumentation"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaDocumentation sınıfı. World Wide Web Consortium (W3C) tarafından belirlenen XML Şema'dan **documentation** öğesini temsil eder. Bu sınıf, C++ içinde bir **annotation** içinde insanlar tarafından okunacak veya kullanılacak bilgileri belirtir."
type: docs
weight: 2500
url: /tr/cpp/system.xml.schema/xmlschemadocumentation/
---
## XmlSchemaDocumentation class


**documentation** öğesini XML [Schema](../) üzerinden World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, insanlar tarafından okunacak veya kullanılacak bilgileri bir **annotation** içinde belirtir.

```cpp
class XmlSchemaDocumentation : public System::Xml::Schema::XmlSchemaObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Language](./get_language/)() | **xml:lang** özniteliğini döndürür. Bu, içeriklerde kullanılan dili gösteren bir belirteç olarak hizmet eder. |
| [get_Markup](./get_markup/)() | belgeleme alt düğümlerini temsil eden [XmlNode](../../system.xml/xmlnode/) nesnelerinin bir dizisini döndürür. |
| [get_Source](./get_source/)() | Bilginin Uniform Resource Identifier (URI) kaynağını döndürür. |
| [set_Language](./set_language/)(const String\&) | **xml:lang** özniteliğini ayarlar. Bu, içeriklerde kullanılan dili gösteren bir belirteç olarak hizmet eder. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | belgeleme alt düğümlerini temsil eden [XmlNode](../../system.xml/xmlnode/) nesnelerinin bir dizisini ayarlar. |
| [set_Source](./set_source/)(const String\&) | Bilginin Uniform Resource Identifier (URI) kaynağını ayarlar. |
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
