---
title: "System::Xml::Schema::XmlSchemaAppInfo sınıfı"
linktitle: "XmlSchemaAppInfo"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAppInfo sınıfı. C++ içinde World Wide Web Consortium (W3C) appinfo öğesini temsil eder."
type: docs
weight: 1000
url: /tr/cpp/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo class


World Wide [Web](../../system.web/) Consortium (W3C) **appinfo** öğesini temsil eder.

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Markup](./get_markup/)() | **appinfo** alt düğümlerini temsil eden [XmlNode](../../system.xml/xmlnode/) nesnelerinin bir dizisini döndürür. |
| [get_Source](./get_source/)() | Uygulama bilgilerinin kaynağını döndürür. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | **appinfo** alt düğümlerini temsil eden [XmlNode](../../system.xml/xmlnode/) nesnelerinin bir dizisini ayarlar. |
| [set_Source](./set_source/)(const String\&) | Uygulama bilgilerinin kaynağını ayarlar. |
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
