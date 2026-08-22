---
title: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri yöntemi"
linktitle: "ResolveUri"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri yöntemi. C++'ta temel ve göreli URI'lerden mutlak URI'yi çözer."
type: docs
weight: 600
url: /tr/cpp/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri method


Temel ve göreli URI'lerden mutlak URI'yi çözer.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Göreli URI'yi çözmek için kullanılan temel URI. |
| relativeUri | String | Çözülecek URI. URI mutlak ya da göreli olabilir. Mutlak ise, bu değer etkili bir şekilde **baseUri** değerini değiştirir. Göreli ise, **baseUri** ile birleştirilerek mutlak bir URI oluşturur. |

### ReturnValue

Mutlak URI'yi temsil eden [Uri](../../../system/uri/) veya göreli URI çözülemezse **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.PUB for C++](../../../)
