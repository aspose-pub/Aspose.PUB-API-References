---
title: "System::Xml::Schema::XmlSchemaRedefine sınıfı"
linktitle: "XmlSchemaRedefine"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaRedefine sınıfı. World Wide Web Consortium (W3C) tarafından belirtilen XML Schema'dan redefine öğesini temsil eder. Bu sınıf, dış şema dosyalarından basit ve karmaşık türleri, grupları ve öznitelik gruplarını geçerli şemada yeniden tanımlamaya izin vermek için kullanılabilir. Ayrıca bu sınıf, C++'ta şema öğeleri için sürümleme sağlamada da kullanılabilir."
type: docs
weight: 5600
url: /tr/cpp/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine class


XML [Schema](../) tarafından World Wide [Web](../../system.web/) Consortium (W3C) olarak belirtilen **redefine** öğesini temsil eder. Bu sınıf, dış şema dosyalarından basit ve karmaşık türleri, grupları ve öznitelik gruplarını geçerli şemada yeniden tanımlamaya izin vermek için kullanılabilir. Ayrıca bu sınıf, şema öğeleri için sürümleme sağlamada da kullanılabilir.

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AttributeGroups](./get_attributegroups/)() | Şemadaki tüm öznitelikler için, **AttributeGroups** değerinin derleme sonrası yorumlamasını tutan [XmlSchemaObjectTable](../xmlschemaobjecttable/) nesnesini döndürür. |
| [get_Groups](./get_groups/)() | Şema içindeki tüm gruplar için [XmlSchemaObjectTable](../xmlschemaobjecttable/) döndürür; bu, **Groups** değerinin derleme sonrası yorumlamasını tutar. |
| [get_Items](./get_items/)() | Aşağıdaki sınıfların koleksiyonunu döndürür: [XmlSchemaAnnotation](../xmlschemaannotation/), [XmlSchemaAttributeGroup](../xmlschemaattributegroup/), [XmlSchemaComplexType](../xmlschemacomplextype/), [XmlSchemaSimpleType](../xmlschemasimpletype/), ve [XmlSchemaGroup](../xmlschemagroup/). |
| [get_SchemaTypes](./get_schematypes/)() | Şema içindeki tüm basit ve karmaşık tipler için [XmlSchemaObjectTable](../xmlschemaobjecttable/) döndürür; bu, **SchemaTypes** değerinin derleme sonrası yorumlamasını tutar. |
| [XmlSchemaRedefine](./xmlschemaredefine/)() | [XmlSchemaRedefine](./) sınıfının yeni bir örneğini başlatır. |
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
