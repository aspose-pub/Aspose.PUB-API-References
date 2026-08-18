---
title: "System::Xml::XmlResolver::ResolveUri method"
linktitle: "ResolveUri"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlResolver::ResolveUri method. Wenn in einer abgeleiteten Klasse überschrieben, löst die Methode die absolute URI aus der Basis- und relativen URI in C++ auf."
type: docs
weight: 200
url: /de/cpp/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri method


Wenn in einer abgeleiteten Klasse überschrieben, löst sie die absolute URI aus der Basis‑ und relativen URIs auf.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
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
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
