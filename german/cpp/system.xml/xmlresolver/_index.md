---
title: "Klasse System::Xml::XmlResolver"
linktitle: "XmlResolver"
second_title: "Aspose.PUB für C++"
description: "Klasse System::Xml::XmlResolver. Löst externe XML-Ressourcen, die durch einen Uniform Resource Identifier (URI) benannt sind, in C++ auf."
type: docs
weight: 3500
url: /de/cpp/system.xml/xmlresolver/
---
## XmlResolver class


Löst externe XML‑Ressourcen auf, die durch einen Uniform Resource Identifier (URI) benannt sind.

```cpp
class XmlResolver : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) | Wenn in einer abgeleiteten Klasse überschrieben, ordnet sie eine URI einem Objekt zu, das die eigentliche Ressource enthält. |
| virtual [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) | Wenn in einer abgeleiteten Klasse überschrieben, löst sie die absolute URI aus der Basis‑ und relativen URIs auf. |
| virtual [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) | Wenn in einer abgeleiteten Klasse überschrieben, legt sie die Anmeldeinformationen fest, die zur Authentifizierung von Webanfragen verwendet werden. |
| virtual [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) | Ermöglicht dem Resolver, Typen zurückzugeben, die nicht Stream sind. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
