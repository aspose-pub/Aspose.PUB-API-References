---
title: "System::Xml::Xsl::XslTransform sınıfı"
linktitle: "XslTransform"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XslTransform sınıfı. C++'ta Dönüşümler için Genişletilebilir Stil Sayfası Dili (XSLT) stil sayfası kullanarak XML verilerini dönüştürür."
type: docs
weight: 700
url: /tr/cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


XML verilerini Extensible Stylesheet Language for Transformations (XSLT) stil sayfası kullanarak dönüştürür.

```cpp
class XslTransform : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | XSLT stil sayfasını [XmlReader](../../system.xml/xmlreader/) içinde yükler. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XSLT stil sayfasını [XmlReader](../../system.xml/xmlreader/) içinde yükler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | IXPathNavigable içinde bulunan XSLT stil sayfasını yükler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | IXPathNavigable içinde bulunan XSLT stil sayfasını yükler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) | XPathNavigator içinde bulunan XSLT stil sayfasını yükler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XPathNavigator içinde bulunan XSLT stil sayfasını yükler. |
| [Load](./load/)(const String\&) | Bir URL tarafından belirtilen XSLT stil sayfasını yükler. |
| [Load](./load/)(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Bir URL tarafından belirtilen XSLT stil sayfasını yükler. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | [XslTransform::Transform](./transform/) yöntemi çağrıldığında harici kaynakları çözmek için kullanılan [XmlResolver](../../system.xml/xmlresolver/) ayarlar. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../system.xml/xmlreader/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../system.xml/xmlreader/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XPathNavigator içindeki XML verilerini belirtilen args kullanarak dönüştürür ve sonucu bir [XmlWriter](../../system.xml/xmlwriter/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | XPathNavigator içindeki XML verilerini belirtilen args kullanarak dönüştürür ve sonucu bir [XmlWriter](../../system.xml/xmlwriter/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Stream'e çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Stream'e çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | XPathNavigator içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../system.xml/xmlreader/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlReader](../../system.xml/xmlreader/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir TextWriter'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Stream'e çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir Stream'e çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlWriter](../../system.xml/xmlwriter/)'a çıkarır. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | IXPathNavigable içindeki XML verilerini belirtilen **args** kullanarak dönüştürür ve sonucu bir [XmlWriter](../../system.xml/xmlwriter/)'a çıkarır. |
| [Transform](./transform/)(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Girdi dosyasındaki XML verilerini dönüştürür ve sonucu bir çıktı dosyasına yazar. |
| [Transform](./transform/)(const String\&, const String\&) | Girdi dosyasındaki XML verilerini dönüştürür ve sonucu bir çıktı dosyasına yazar. |
| [XslTransform](./xsltransform/)() | Yeni bir [XslTransform](./) sınıfı örneği oluşturur. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PUB for C++](../../)
