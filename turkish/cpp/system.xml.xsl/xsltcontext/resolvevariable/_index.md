---
title: "System::Xml::Xsl::XsltContext::ResolveVariable metodu"
linktitle: "ResolveVariable"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::XsltContext::ResolveVariable metodu. Türetilmiş bir sınıfta geçersiz kılındığında, bir değişken referansını çözer ve C++'da değişkeni temsil eden bir IXsltContextVariable döndürür."
type: docs
weight: 500
url: /tr/cpp/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable method


Türetilmiş bir sınıfta geçersiz kılındığında, bir değişken referansını çözer ve değişkeni temsil eden bir [IXsltContextVariable](../../ixsltcontextvariable/) döndürür.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | String | Değişkenin, [XPath](../../../system.xml.xpath/) ifadesinde göründüğü önek. |
| ad | String | Değişkenin adı. |

### ReturnValue

Çalışma zamanında değişkeni temsil eden bir [IXsltContextVariable](../../ixsltcontextvariable/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
