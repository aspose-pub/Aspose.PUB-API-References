---
title: "System::Xml::Xsl::IXsltContextVariable sınıfı"
linktitle: "IXsltContextVariable"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::IXsltContextVariable sınıfı. Çalışma zamanında C++ içinde stil sayfasında tanımlanan bir değişkene bir arabirim sağlar."
type: docs
weight: 200
url: /tr/cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Çalışma zamanında yürütme sırasında stil sayfasında tanımlanan belirli bir değişkene bir arabirim sağlar.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Değişkeni çalışma zamanında değerlendirir ve değişkenin değerini temsil eden bir nesne döndürür. |
| virtual [get_IsLocal](./get_islocal/)() | Değişkenin yerel olup olmadığını gösteren bir değer döndürür. |
| virtual [get_IsParam](./get_isparam/)() | Değişkenin Extensible Stylesheet Language Transformations (XSLT) parametresi olup olmadığını gösteren bir değer döndürür. Bu, bir stil sayfası veya şablon için bir parametre olabilir. |
| virtual [get_VariableType](./get_variabletype/)() | Değişkenin XML Path Language ([XPath](../../system.xml.xpath/)) türünü temsil eden XPathResultType değerini döndürür. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PUB for C++](../../)
