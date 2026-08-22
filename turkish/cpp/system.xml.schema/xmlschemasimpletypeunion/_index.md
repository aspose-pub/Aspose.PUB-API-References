---
title: "System::Xml::Schema::XmlSchemaSimpleTypeUnion sınıfı"
linktitle: "XmlSchemaSimpleTypeUnion"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaSimpleTypeUnion sınıfı. XML Şeması'ndan basit tipler için birleşim (union) öğesini, World Wide Web Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bir union veri tipi, bir simpleType'ın içeriğini belirtmek için kullanılabilir. simpleType öğesinin değeri, birleşimde belirtilen alternatif veri tiplerinden oluşan bir kümeden herhangi biri olmalıdır. Union tipleri her zaman türetilmiş tiplerdir ve C++'ta en az iki alternatif veri tipini içermelidir."
type: docs
weight: 6600
url: /tr/cpp/system.xml.schema/xmlschemasimpletypeunion/
---
## XmlSchemaSimpleTypeUnion class


XML [Schema](../) üzerinden **union** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bir **union** veri tipi, bir **simpleType**'ın içeriğini belirtmek için kullanılabilir. **simpleType** öğesinin değeri, birleşimde belirtilen alternatif veri tiplerinden oluşan bir kümeden herhangi biri olmalıdır. Union tipleri her zaman türetilmiş tiplerdir ve en az iki alternatif veri tipini içermelidir.

```cpp
class XmlSchemaSimpleTypeUnion : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_BaseMemberTypes](./get_basemembertypes/)() | **simpleType** öğesinin tipini temsil eden [XmlSchemaSimpleType](../xmlschemasimpletype/) nesnelerinin bir dizisini, simple type'ın [XmlSchemaSimpleTypeUnion::get_BaseTypes](./get_basetypes/) ve [XmlSchemaSimpleTypeUnion::get_MemberTypes](./get_membertypes/) değerlerine dayanarak döndürür. |
| [get_BaseTypes](./get_basetypes/)() | Temel tiplerin koleksiyonunu döndürür. |
| [get_MemberTypes](./get_membertypes/)() | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) tanımlı yerleşik veri tiplerinin veya **simpleType** öğelerinin nitelikli üye adlarının dizisini döndürür. |
| [set_MemberTypes](./set_membertypes/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) tanımlı yerleşik veri tiplerinin veya **simpleType** öğelerinin nitelikli üye adlarının dizisini ayarlar. |
| [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/)() | [XmlSchemaSimpleTypeUnion](./) sınıfının yeni bir örneğini başlatır. |
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
