---
title: "System::Xml::Schema::XmlAtomicValue sınıfı"
linktitle: "XmlAtomicValue"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlAtomicValue sınıfı. Doğrulanmış bir XML öğesi veya özniteliğinin tiplenmiş değerini temsil eder. XmlAtomicValue sınıfı C++'ta devralınamaz."
type: docs
weight: 300
url: /tr/cpp/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue class


Doğrulanmış bir XML öğesi veya özniteliğinin tiplenmiş değerini temsil eder. [XmlAtomicValue](./) sınıfı devralınamaz.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone](./clone/)() | Bu [XmlAtomicValue](./) nesnesinin bir kopyasını döndürür. |
| [get_IsNode](./get_isnode/)() override | Doğrulanmış XML öğesi veya özniteliğinin bir [XPath](../../system.xml.xpath/) düğümü mü yoksa atomik bir değer mi olduğunu gösteren bir değer döndürür. |
| [get_TypedValue](./get_typedvalue/)() override | Geçerli doğrulanmış XML öğesi veya özniteliğini, şema tipine göre en uygun tipte kutulanmış bir nesne olarak döndürür. |
| [get_Value](./get_value/)() override | Doğrulanmış XML öğesi veya özniteliğinin [String](../../system/string/) değerini döndürür. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Doğrulanmış XML öğesi veya özniteliğinin değerini bir [Boolean](../../system/boolean/) olarak döndürür. |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Doğrulanmış XML öğesi veya özniteliğinin değerini bir [DateTime](../../system/datetime/) olarak döndürür. |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Doğrulanmış XML öğesi veya özniteliğinin değerini bir [Double](../../system/double/) olarak döndürür. |
| [get_ValueAsInt](./get_valueasint/)() override | Doğrulanmış XML öğesi veya özniteliğinin değerini bir [Int32](../../system/int32/) olarak döndürür. |
| [get_ValueAsLong](./get_valueaslong/)() override | Doğrulanmış XML öğesi veya özniteliğinin değerini bir [Int64](../../system/int64/) olarak döndürür. |
| [get_ValueType](./get_valuetype/)() override | Doğrulanmış XML öğesi veya özniteliğinin tipini döndürür. |
| [get_XmlType](./get_xmltype/)() override | Doğrulanmış XML öğesi veya özniteliği için [XmlSchemaType](../xmlschematype/) döndürür. |
| [ToString](./tostring/)() const override | Doğrulanmış XML öğesi veya özniteliğinin [String](../../system/string/) değerini döndürür. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Doğrulanmış XML öğesi veya özniteliğinin değerini, ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesi kullanılarak belirtilen tipte döndürür. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XPathItem](../../system.xml.xpath/xpathitem/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
