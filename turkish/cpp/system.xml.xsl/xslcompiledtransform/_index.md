---
title: "System::Xml::Xsl::XslCompiledTransform class"
linktitle: "XslCompiledTransform"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XslCompiledTransform sınıfı. C++'ta bir XSLT stil sayfası kullanarak XML verilerini dönüştürür."
type: docs
weight: 300
url: /tr/cpp/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform class


XML verilerini bir XSLT stil sayfası kullanarak dönüştürür.

```cpp
class XslCompiledTransform : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_OutputSettings](./get_outputsettings/)() | Stil sayfasının **xsl:output** öğesinden türetilen çıktı bilgilerini içeren bir [XmlWriterSettings](../../system.xml/xmlwritersettings/) nesnesi döndürür. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | [XmlReader](../../system.xml/xmlreader/) içinde bulunan stil sayfasını derler. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | [XmlReader](../../system.xml/xmlreader/) içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../system.xml/xmlresolver/) herhangi bir XSLT **import** veya **include** öğesini çözer ve XSLT ayarları stil sayfası için izinleri belirler. |
| [Load](./load/)(const String\&) | Belirtilen URI'deki stil sayfasını yükler ve derler. |
| [Load](./load/)(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | URI tarafından belirtilen XSLT stil sayfasını yükler ve derler. [XmlResolver](../../system.xml/xmlresolver/) herhangi bir XSLT **import** veya **include** öğesini çözer ve XSLT ayarları stil sayfası için izinleri belirler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | IXPathNavigable nesnesinde bulunan stil sayfasını derler. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) | IXPathNavigable içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../system.xml/xmlresolver/) herhangi bir XSLT **import** veya **include** öğesini çözer ve XSLT ayarları stil sayfası için izinleri belirler. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) | IXPathNavigable nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | IXPathNavigable nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | IXPathNavigable nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | IXPathNavigable nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XmlWriter\>\&) | URI tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | URI tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | URI tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a yazar. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | URI tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| [Transform](./transform/)(const String\&, const String\&) | URI tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir dosyaya yazar. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../system.xml/xmlresolver/) XSLT **document()** işlevini çözer. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | IXPathNavigable nesnesi tarafından belirtilen girdi belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla yazar. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../system.xml/xmlresolver/) XSLT **document()** işlevini çözer. |
| [XslCompiledTransform](./xslcompiledtransform/)() | [XslCompiledTransform](./) sınıfının yeni bir örneğini başlatır. |
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
