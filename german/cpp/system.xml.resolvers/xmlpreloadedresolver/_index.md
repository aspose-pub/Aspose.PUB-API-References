---
title: "System::Xml::Resolvers::XmlPreloadedResolver‑Klasse"
linktitle: "XmlPreloadedResolver"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Resolvers::XmlPreloadedResolver‑Klasse. Stellt eine Klasse dar, die verwendet wird, um den Cache in C++ mit DTDs oder XML‑Streams vorzupopulieren."
type: docs
weight: 100
url: /de/cpp/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver class


Stellt eine Klasse dar, die verwendet wird, um den Cache mit DTDs oder XML‑Streams vorab zu füllen.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) | Fügt dem [XmlPreloadedResolver](./)-Speicher ein Byte‑Array hinzu und ordnet es einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Fügt dem [XmlPreloadedResolver](./)-Speicher ein Byte‑Array hinzu und ordnet es einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) | Fügt dem [XmlPreloadedResolver](./)-Speicher einen Stream hinzu und ordnet ihn einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const String\&) | Fügt dem [XmlPreloadedResolver](./)-Speicher einen String mit vorab geladenen Daten hinzu und ordnet ihn einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben. |
| [get_PreloadedUris](./get_preloadeduris/)() | Gibt eine Sammlung von vorab geladenen URIs zurück. |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält. |
| [Remove](./remove/)(const SharedPtr\<Uri\>\&) | Entfernt die Daten, die der URI im [XmlPreloadedResolver](./) entsprechen. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Löst den absoluten URI aus dem Basis- und relativen URI auf. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Legt die Anmeldeinformationen fest, die zur Authentifizierung der zugrunde liegenden [Net::WebRequest](../../system.net/webrequest/) verwendet werden. |
| [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) override | Ermittelt, ob der Resolver andere Typen als nur Stream unterstützt. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)() | Initialisiert eine neue Instanz der [XmlPreloadedResolver](./)-Klasse. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(XmlKnownDtds) | Initialisiert eine neue Instanz der [XmlPreloadedResolver](./)-Klasse mit den angegebenen vorab geladenen bekannten DTDs. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&) | Initialisiert eine neue Instanz der [XmlPreloadedResolver](./)-Klasse mit dem angegebenen Fallback‑Resolver. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) | Initialisiert eine neue Instanz der [XmlPreloadedResolver](./)-Klasse mit dem angegebenen Fallback‑Resolver und vorab geladenen bekannten DTDs. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) | Initialisiert eine neue Instanz der [XmlPreloadedResolver](./)-Klasse mit dem angegebenen Fallback‑Resolver, vorab geladenen bekannten DTDs und einem URI‑Gleichheitsvergleich. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [XmlResolver](../../system.xml/xmlresolver/)
* Namespace [System::Xml::Resolvers](../)
* Library [Aspose.PUB for C++](../../)
