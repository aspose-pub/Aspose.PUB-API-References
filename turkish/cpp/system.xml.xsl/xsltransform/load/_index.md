---
title: "System::Xml::Xsl::XslTransform::Load yöntemi"
linktitle: "Load"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XslTransform::Load yöntemi. C++'ta IXPathNavigable içinde bulunan XSLT stil sayfasını yükler."
type: docs
weight: 200
url: /tr/cpp/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


IXPathNavigable içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) veya XSLT stil sayfasını içeren bir XPathDocument olabilir. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


IXPathNavigable içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) veya XSLT stil sayfasını içeren bir XPathDocument olabilir. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Herhangi bir **xsl:import** ve **xsl:include** öğesinde başvurulan stil sayfalarını yüklemek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


XPathNavigator içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stil sayfası | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XSLT stil sayfasını içeren bir XPathNavigator nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


XPathNavigator içinde bulunan XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stil sayfası | const SharedPtr\<System::Xml::XPath::XPathNavigator\>\& | XSLT stil sayfasını içeren bir XPathNavigator nesnesi. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Herhangi bir **xsl:import** ve **xsl:include** öğesinde başvurulan stil sayfalarını yüklemek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


XSLT stil sayfasını içeren [XmlReader](../../../system.xml/xmlreader/) öğesini yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | XSLT stil sayfasını içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


XSLT stil sayfasını içeren [XmlReader](../../../system.xml/xmlreader/) öğesini yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const SharedPtr\<XmlReader\>\& | XSLT stil sayfasını içeren bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | Herhangi bir **xsl:import** ve **xsl:include** öğesinde başvurulan stil sayfalarını yüklemek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, dış kaynaklar çözülmez. [XmlResolver](../../../system.xml/xmlresolver/) bu yöntem tamamlandıktan sonra önbelleğe alınmaz. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const String\&) method


Bir URL tarafından belirtilen XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const String\& | Yüklenecek XSLT stil sayfasını belirten URL. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Bir URL tarafından belirtilen XSLT stil sayfasını yükler.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | const String\& | Yüklenecek XSLT stil sayfasını belirten URL. |
| resolver | const SharedPtr\<System::Xml::XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) stil sayfasını ve **xsl:import** ve **xsl:include** öğelerinde başvurulan herhangi bir stil sayfasını (stil sayfalarını) yüklemek için kullanılacak. Bu **nullptr** ise, kullanıcı kimlik bilgileri olmayan varsayılan bir [XmlUrlResolver](../../../system.xml/xmlurlresolver/) stil sayfasını açmak için kullanılır. Varsayılan [XmlUrlResolver](../../../system.xml/xmlurlresolver/) stil sayfasındaki dış kaynakları çözümlemek için kullanılmaz, bu yüzden **xsl:import** ve **xsl:include** öğeleri çözülmez. Bu yöntem tamamlandıktan sonra [XmlResolver](../../../system.xml/xmlresolver/) önbelleğe alınmaz. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XslTransform](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
