---
title: "System::Xml::Xsl::IXsltContextFunction sınıfı"
linktitle: "IXsltContextFunction"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::IXsltContextFunction sınıfı. Çalışma zamanında C++ içinde Extensible Stylesheet Language for Transformations (XSLT) stil sayfasında tanımlanan bir fonksiyona bir arabirim sağlar."
type: docs
weight: 100
url: /tr/cpp/system.xml.xsl/ixsltcontextfunction/
---
## IXsltContextFunction class


Çalışma zamanı yürütmesi sırasında Extensible Stylesheet Language for Transformations (XSLT) stil sayfasında tanımlı bir işlev için bir arayüz sağlar.

```cpp
class IXsltContextFunction : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [get_ArgTypes](./get_argtypes/)() | Fonksiyonun argüman listesi için sağlanan XML Path Language ([XPath](../../system.xml.xpath/)) türlerini döndürür. Bu bilgi, fonksiyonun imzasını keşfetmek için kullanılabilir ve aşırı yüklenmiş fonksiyonlar arasında ayrım yapmanıza olanak tanır. |
| virtual [get_Maxargs](./get_maxargs/)() | Fonksiyon için azami argüman sayısını döndürür. Bu, kullanıcıların aşırı yüklenmiş fonksiyonlar arasında ayrım yapmasını sağlar. |
| virtual [get_Minargs](./get_minargs/)() | Fonksiyon için asgari argüman sayısını döndürür. Bu, kullanıcıların aşırı yüklenmiş fonksiyonlar arasında ayrım yapmasını sağlar. |
| virtual [get_ReturnType](./get_returntype/)() | Fonksiyonun döndürdüğü [XPath](../../system.xml.xpath/) türünü temsil eden XPathResultType değerini döndürür. |
| virtual [Invoke](./invoke/)(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) | Verilen bağlamda verilen argümanlarla fonksiyonu çağırmak için yöntemi sağlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PUB for C++](../../)
