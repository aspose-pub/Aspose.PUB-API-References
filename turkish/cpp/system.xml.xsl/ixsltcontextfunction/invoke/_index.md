---
title: "System::Xml::Xsl::IXsltContextFunction::Invoke yöntemi"
linktitle: "Invoke"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Xsl::IXsltContextFunction::Invoke yöntemi. C++'ta verilen bağlamda verilen argümanlarla fonksiyonu çağırmak için yöntemi sağlar."
type: docs
weight: 500
url: /tr/cpp/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke method


Verilen bağlamda verilen argümanlarla fonksiyonu çağırmak için yöntemi sağlar.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xsltContext | SharedPtr\\<XsltContext\\> | Fonksiyon çağrısı için XSLT bağlamı. |
| argümanlar | ArrayPtr\\<SharedPtr\\<Object\\>\\> | Fonksiyon çağrısının argümanları. Her argüman dizi içinde bir öğedir. |
| docContext | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Fonksiyon çağrısı için bağlam düğümü. |

### ReturnValue

Fonksiyonun dönüş değerini temsil eden bir [Object](../../../system.object/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PUB for C++](../../../)
