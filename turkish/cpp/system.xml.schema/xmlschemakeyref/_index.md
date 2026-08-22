---
title: "System::Xml::Schema::XmlSchemaKeyref sınıfı"
linktitle: "XmlSchemaKeyref"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaKeyref sınıfı. Bu sınıf, C++'ta World Wide Web Consortium (W3C) tarafından belirlenen XMLSchema'dan keyref öğesini temsil eder."
type: docs
weight: 4000
url: /tr/cpp/system.xml.schema/xmlschemakeyref/
---
## XmlSchemaKeyref class


Bu sınıf, Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirlenen XMLSchema'dan **keyref** öğesini temsil eder.

```cpp
class XmlSchemaKeyref : public System::Xml::Schema::XmlSchemaIdentityConstraint
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Refer](./get_refer/)() | Bu kısıtlamanın başka bir basit veya karmaşık türde başvurduğu anahtarın adını döndürür. |
| [set_Refer](./set_refer/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu kısıtlamanın başka bir basit veya karmaşık türde başvurduğu anahtarın adını ayarlar. |
| [XmlSchemaKeyref](./xmlschemakeyref/)() | Yeni bir [XmlSchemaKeyref](./) sınıfı örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaIdentityConstraint](../xmlschemaidentityconstraint/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
