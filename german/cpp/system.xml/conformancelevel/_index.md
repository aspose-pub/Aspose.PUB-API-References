---
title: "System::Xml::ConformanceLevel enum"
linktitle: "ConformanceLevel"
second_title: "Aspose.PUB für C++"
description: "System::Xml::ConformanceLevel enum. Gibt die Menge an Eingabe- oder Ausgabeüberprüfungen an, die XmlReader- und XmlWriter-Objekte in C++ durchführen."
type: docs
weight: 4600
url: /de/cpp/system.xml/conformancelevel/
---
## ConformanceLevel enum


Gibt die Menge an Eingabe- oder Ausgabeüberprüfungen an, die die [XmlReader](../xmlreader/)- und [XmlWriter](../xmlwriter/)-Objekte durchführen.

```cpp
enum class ConformanceLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Das [XmlReader](../xmlreader/)- oder [XmlWriter](../xmlwriter/)-Objekt erkennt automatisch, ob eine Dokument‑ oder Fragment‑Überprüfung durchgeführt werden soll, und führt die entsprechende Prüfung durch. Wenn Sie ein weiteres [XmlReader](../xmlreader/)- oder [XmlWriter](../xmlwriter/)-Objekt einbinden, führt das äußere Objekt keine zusätzliche Konformitätsprüfung durch. Die Konformitätsprüfung wird dem zugrunde liegenden Objekt überlassen. |
| Fragment | 1 | Die XML‑Daten sind ein [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), wie vom W3C definiert. Dieses Konformitätsniveau stellt ein XML‑Dokument dar, das möglicherweise kein Root‑Element hat, aber ansonsten wohlgeformt ist. Dieses Prüfungsniveau stellt sicher, dass der gelesene oder geschriebene Stream von jedem Prozessor als [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) konsumiert werden kann. |
| Document | 2 | Die XML‑Daten entsprechen den Regeln für ein wohlgeformtes [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), wie vom W3C definiert. Dieses Prüfungsniveau stellt sicher, dass der gelesene oder geschriebene Stream von jedem Prozessor als [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) konsumiert werden kann. |

## Siehe auch

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
