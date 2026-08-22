---
title: "System::Xml::Schema::XmlSchemaParticle sınıfı"
linktitle: "XmlSchemaParticle"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaParticle sınıfı. C++'ta tüm particle türleri (ör. XmlSchemaAny) için temel sınıf olan bir temel sınıftır."
type: docs
weight: 5400
url: /tr/cpp/system.xml.schema/xmlschemaparticle/
---
## XmlSchemaParticle class


Bunun temel sınıfı, tüm parçacık türleri için temel sınıftır (örn. [XmlSchemaAny](../xmlschemaany/)).

```cpp
class XmlSchemaParticle : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_MaxOccurs](./get_maxoccurs/)() | Parçacığın oluşabileceği maksimum sayıyı döndürür. |
| [get_MaxOccursString](./get_maxoccursstring/)() | Sayının string değerini döndürür. Parçacığın oluşabileceği maksimum sayı. |
| [get_MinOccurs](./get_minoccurs/)() | Parçacığın oluşabileceği minimum sayıyı döndürür. |
| [get_MinOccursString](./get_minoccursstring/)() | Sayının string değerini döndürür. Parçacığın oluşabileceği minimum sayı. |
| [set_MaxOccurs](./set_maxoccurs/)(Decimal) | Parçacığın oluşabileceği maksimum sayıyı ayarlar. |
| [set_MaxOccursString](./set_maxoccursstring/)(const String\&) | Sayının string değerini ayarlar. Parçacığın oluşabileceği maksimum sayı. |
| [set_MinOccurs](./set_minoccurs/)(Decimal) | Parçacığın oluşabileceği minimum sayıyı ayarlar. |
| [set_MinOccursString](./set_minoccursstring/)(const String\&) | Sayının string değerini ayarlar. Parçacığın oluşabileceği minimum sayı. |
| [XmlSchemaParticle](./xmlschemaparticle/)() | [XmlSchemaParticle](./) sınıfının yeni bir örneğini başlatır. |
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
