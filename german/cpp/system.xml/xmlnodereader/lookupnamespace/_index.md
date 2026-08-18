---
title: "System::Xml::XmlNodeReader::LookupNamespace method"
linktitle: "LookupNamespace"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlNodeReader::LookupNamespace method. Löst ein Namespace-Präfix im Geltungsbereich des aktuellen Elements''s in C++ auf."
type: docs
weight: 2500
url: /de/cpp/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace method


Löst ein Namespace-Präfix im Geltungsbereich des aktuellen Elements auf.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | const String\& | Das Präfix, dessen Namespace-URI Sie auflösen möchten. Um den Standard‑Namespace zu verwenden, übergeben Sie eine leere Zeichenfolge. Diese Zeichenfolge muss nicht atomisiert werden. |

### ReturnValue

Der Namespace-URI, dem das Präfix zugeordnet ist, oder **nullptr**, falls kein passendes Präfix gefunden wird.

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
