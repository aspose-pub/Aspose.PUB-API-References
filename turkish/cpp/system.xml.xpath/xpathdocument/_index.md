---
title: "System::Xml::XPath::XPathDocument sınıfı"
linktitle: "XPathDocument"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XPath::XPathDocument sınıfı. C++'da XPath veri modelini kullanarak bir XML belgesinin hızlı, yalnızca okunabilir, bellek içi temsilini sağlar."
type: docs
weight: 200
url: /tr/cpp/system.xml.xpath/xpathdocument/
---
## XPathDocument class


[XPath](../) veri modelini kullanarak bir XML belgesinin hızlı, yalnızca okunabilir, bellek içi temsilini sağlar.

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateNavigator](./createnavigator/)() override | Bu [XPathDocument](./) içindeki düğümler arasında gezinmek için yalnızca okunabilir bir [XPathNavigator](../xpathnavigator/) nesnesi başlatır. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinde bulunan XML verilerinden [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&, XmlSpace) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinde bulunan XML verilerinden, belirtilen boşluk işleme ayarıyla [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::TextReader\>\&) | Belirtilen TextReader nesnesinde bulunan XML verisinden [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::Stream\>\&) | Belirtilen Stream nesnesindeki XML verisinden [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
| [XPathDocument](./xpathdocument/)(const String\&) | Belirtilen dosyadaki XML verisinden [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
| [XPathDocument](./xpathdocument/)(const String\&, XmlSpace) | Boşluk işleme ayarıyla belirtilen dosyadaki XML verisinden [XPathDocument](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PUB for C++](../../)
