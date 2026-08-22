---
title: "System::Xml::XmlImplementation sınıfı"
linktitle: "XmlImplementation"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlImplementation sınıfı. C++'ta bir dizi XmlDocument nesnesi için bağlamı tanımlar."
type: docs
weight: 2000
url: /tr/cpp/system.xml/xmlimplementation/
---
## XmlImplementation class


[XmlDocument](../xmldocument/) nesnelerinin bir kümesi için bağlamı tanımlar.

```cpp
class XmlImplementation : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [CreateDocument](./createdocument/)() | Yeni bir [XmlDocument](../xmldocument/) oluşturur. |
| [HasFeature](./hasfeature/)(const String\&, const String\&) | Belge [Object](../../system/object/) Modeli (DOM) uygulamasının belirli bir özelliği uygulayıp uygulamadığını test eder. |
| [XmlImplementation](./xmlimplementation/)() | [XmlImplementation](./) sınıfının yeni bir örneğini başlatır. |
| [XmlImplementation](./xmlimplementation/)(const SharedPtr\<XmlNameTable\>\&) | [XmlImplementation](./) sınıfının yeni bir örneğini, belirtilen [XmlNameTable](../xmlnametable/) ile başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
