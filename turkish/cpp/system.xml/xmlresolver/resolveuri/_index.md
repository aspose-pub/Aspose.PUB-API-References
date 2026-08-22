---
title: "System::Xml::XmlResolver::ResolveUri yöntemi"
linktitle: "ResolveUri"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlResolver::ResolveUri yöntemi. Türetilmiş bir sınıfta geçersiz kılındığında, C++'ta temel ve göreli URI'lardan mutlak URI'yu çözer."
type: docs
weight: 200
url: /tr/cpp/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri method


Türetilmiş bir sınıfta geçersiz kılındığında, temel ve göreli URI'lerden mutlak URI'yi çözer.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Göreli URI'yi çözmek için kullanılan temel URI. |
| relativeUri | String | Çözülecek URI. URI mutlak ya da göreli olabilir. Mutlak ise, bu değer etkili bir şekilde **baseUri** değerini değiştirir. Göreli ise, **baseUri** ile birleştirilerek mutlak bir URI oluşturur. |

### ReturnValue

Göreli URI çözülemezse mutlak URI veya **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
