---
title: "System::Xml::XPath::XPathItem sınıfı"
linktitle: "XPathItem"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathItem sınıfı. C++'da XQuery 1.0 ve XPath 2.0 Veri Modelinde bir öğeyi temsil eder."
type: docs
weight: 400
url: /tr/cpp/system.xml.xpath/xpathitem/
---
## XPathItem class


XQuery 1.0 ve [XPath](../) 2.0 [Data](../../system.data/) Modelinde bir öğeyi temsil eder.

```cpp
class XPathItem : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [get_IsNode](./get_isnode/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin bir [XPath](../) düğümü mü yoksa atomik bir değer mi olduğunu gösteren bir değer alır. |
| virtual [get_TypedValue](./get_typedvalue/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli öğeyi şema tipine göre en uygun türde kutulanmış bir nesne olarak alır. |
| virtual [get_Value](./get_value/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin **string** değerini alır. |
| virtual [get_ValueAsBoolean](./get_valueasboolean/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin değerini bir [Boolean](../../system/boolean/) olarak alır. |
| virtual [get_ValueAsDateTime](./get_valueasdatetime/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin değerini bir [DateTime](../../system/datetime/) olarak alır. |
| virtual [get_ValueAsDouble](./get_valueasdouble/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin değerini bir [Double](../../system/double/) olarak alır. |
| virtual [get_ValueAsInt](./get_valueasint/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin değerini bir [Int32](../../system/int32/) olarak alır. |
| virtual [get_ValueAsLong](./get_valueaslong/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin değerini bir [Int64](../../system/int64/) olarak alır. |
| virtual [get_ValueType](./get_valuetype/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin tipini alır. |
| virtual [get_XmlType](./get_xmltype/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğe için XmlSchemaType'ı alır. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&) | Öğenin değerini belirtilen türde döndürür. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Türetilmiş bir sınıfta geçersiz kılındığında, ad alanı öneklerini çözmek için belirtilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesi kullanılarak belirtilen türde öğenin değerini döndürür. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PUB for C++](../../)
