---
title: "System::Xml::Schema::XmlSchemaIdentityConstraint sınıfı"
linktitle: "XmlSchemaIdentityConstraint"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaIdentityConstraint sınıfı. C++'ta kimlik kısıtlamaları için sınıf: key, keyref ve unique öğeleri."
type: docs
weight: 3400
url: /tr/cpp/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint class


Kimlik kısıtlamaları için sınıf: **key**, **keyref**, ve **unique** öğeleri.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Fields](./get_fields/)() | XML Yol Dili ([XPath](../../system.xml.xpath/)) ifadesi seçicisi için alt öğe olarak uygulanan alanların koleksiyonunu döndürür. |
| [get_Name](./get_name/)() | Kimlik kısıtlamasının adını döndürür. |
| [get_QualifiedName](./get_qualifiedname/)() | Kimlik kısıtlamasının nitelikli adını döndürür; bu, **QualifiedName** değerinin derleme sonrası yorumlamasını tutar. |
| [get_Selector](./get_selector/)() | [XPath](../../system.xml.xpath/) ifadesinin **selector** öğesini döndürür. |
| [set_Name](./set_name/)(const String\&) | Kimlik kısıtlamasının adını ayarlar. |
| [set_Selector](./set_selector/)(const SharedPtr\<XmlSchemaXPath\>\&) | [XPath](../../system.xml.xpath/) ifadesinin **selector** öğesini ayarlar. |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | Yeni bir [XmlSchemaIdentityConstraint](./) sınıf örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
