---
title: "System::Xml::XmlReader::LookupNamespace Methode"
linktitle: "LookupNamespace"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlReader::LookupNamespace-Methode. Wenn sie in einer abgeleiteten Klasse überschrieben wird, löst sie ein Namespace-Präfix im Geltungsbereich des aktuellen Elements in C++ auf."
type: docs
weight: 3100
url: /de/cpp/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace method


Wird in einer abgeleiteten Klasse überschrieben, löst ein Namensraum‑Präfix im Geltungsbereich des aktuellen Elements auf.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | const String\& | Das Präfix, dessen Namespace-URI Sie auflösen möchten. Um den Standard‑Namespace zu verwenden, übergeben Sie eine leere Zeichenfolge. |

### ReturnValue

Der Namespace-URI, dem das Präfix zugeordnet ist, oder **nullptr**, falls kein passendes Präfix gefunden wird.

## Siehe auch

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
