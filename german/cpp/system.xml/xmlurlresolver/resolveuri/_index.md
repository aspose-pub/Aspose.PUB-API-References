---
title: "System::Xml::XmlUrlResolver::ResolveUri Methode"
linktitle: "ResolveUri"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlUrlResolver::ResolveUri-Methode. Löst die absolute URI aus der Basis‑ und relativen URI in C++ auf."
type: docs
weight: 300
url: /de/cpp/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri method


Löst den absoluten URI aus dem Basis- und relativen URI auf.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | SharedPtr\<Uri\> | Die Basis‑URI, die zum Auflösen der relativen URI verwendet wird. |
| relativeUri | String | Die aufzulösende URI. Die URI kann absolut oder relativ sein. Ist sie absolut, ersetzt dieser Wert effektiv den **baseUri**‑Wert. Ist sie relativ, wird sie mit dem **baseUri** kombiniert, um eine absolute URI zu erzeugen. |

### ReturnValue

Die absolute URI oder **nullptr**, falls die relative URI nicht aufgelöst werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
