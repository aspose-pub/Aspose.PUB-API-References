---
title: "System::Uri::TryCreate-Methode"
linktitle: "TryCreate"
second_title: "Aspose.PUB für C++"
description: "System::Uri::TryCreate-Methode. Erstellt ein Uri-Objekt aus den angegebenen Basis- und relativen URIs in C++."
type: docs
weight: 4400
url: /de/cpp/system/uri/trycreate/
---
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Erstellt ein [Uri](../)-Objekt aus den angegebenen Basis- und relativen URIs.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Der Basis-URI |
| relativeUri | const SharedPtr\<Uri\>\& | Der relative URI, der zum Basis-URI hinzugefügt wird |
| result | SharedPtr\<Uri\>\& | Das Ausgabeargument, das bei erfolgreicher Erstellung auf das neu erstellte [Uri](../)-Objekt beim Methodenrückkehr verweist |

### ReturnValue

True, wenn die Erstellung erfolgreich war, sonst - false

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Erstellt ein [Uri](../)-Objekt aus dem angegebenen [Uri](../)-Objekt, das den Basis-URI darstellt, und der Zeichenkettenrepräsentation des relativen URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Der Basis-URI |
| relativeUri | const String\& | Der relative URI, der zum Basis-URI hinzugefügt wird |
| result | SharedPtr\<Uri\>\& | Das Ausgabeargument, das bei erfolgreicher Erstellung auf das neu erstellte [Uri](../)-Objekt beim Methodenrückkehr verweist |

### ReturnValue

True, wenn die Erstellung erfolgreich war, sonst - false

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Erstellt ein [Uri](../)-Objekt, das den angegebenen URI darstellt; ein Argument gibt den URI-Typ an.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriString | const String\& | Die Zeichenkette URI, die vom zu konstruierenden Objekt dargestellt wird |
| uriKind | UriKind | Gibt die Art der URI an |
| result | SharedPtr\<Uri\>\& | Das Ausgabeargument, das bei erfolgreicher Erstellung auf das neu erstellte [Uri](../)-Objekt beim Methodenrückkehr verweist |

### ReturnValue

True, wenn die Erstellung erfolgreich war, sonst - false

## Siehe auch

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
