---
title: "System::Uri::MakeRelative Methode"
linktitle: "MakeRelative"
second_title: "Aspose.PUB für C++"
description: "System::Uri::MakeRelative Methode. Bestimmt die Differenz zwischen zwei Uri-Instanzen in C++."
type: docs
weight: 3000
url: /de/cpp/system/uri/makerelative/
---
## Uri::MakeRelative method


Bestimmt die Differenz zwischen zwei [Uri](../)-Instanzen.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| toUri | const SharedPtr\<Uri\>\& | Die URI, die mit der aktuellen URI verglichen werden soll |

### ReturnValue

Wenn der Hostname und das Schema der von dem aktuellen Objekt und **toUri** dargestellten URIs identisch sind, gibt diese Methode einen [String](../../string/) zurück, der eine relative [Uri](../) darstellt, die, wenn sie an die aktuelle URI-Instanz angehängt wird, **toUri** ergibt. Ist der Hostname oder das Schema unterschiedlich, gibt diese Methode einen [String](../../string/) zurück, der den **uri**-Parameter darstellt.

## Siehe auch

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
