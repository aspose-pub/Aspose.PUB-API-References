---
title: "System::Xml::Schema::XmlSchemaValidationFlags Enum"
linktitle: "XmlSchemaValidationFlags"
second_title: "Aspose.PUB für C++"
description: "System::Xml::Schema::XmlSchemaValidationFlags Enum. Gibt die Optionen zur Schema‑Validierung an, die von den Klassen XmlSchemaValidator und XmlReader in C++ verwendet werden."
type: docs
weight: 7900
url: /de/cpp/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum


Gibt die Optionen zur Schema‑Validierung an, die von den Klassen [XmlSchemaValidator](../xmlschemavalidator/) und [XmlReader](../../system.xml/xmlreader/) verwendet werden.

```cpp
enum class XmlSchemaValidationFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Verarbeite keine Identitätsbeschränkungen, Inline‑Schemas, Schema‑Standort‑Hinweise oder melde keine Schema‑Validierungswarnungen. |
| ProcessInlineSchema | 1 | Verarbeite während der Validierung gefundene Inline‑Schemas. |
| ProcessSchemaLocation | 2 | Verarbeite während der Validierung gefundene Schema‑Standort‑Hinweise (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**). |
| ReportValidationWarnings | 4 | Melde während der Validierung gefundene Schema‑Validierungswarnungen. |
| ProcessIdentityConstraints | 8 | Verarbeite während der Validierung gefundene Identitätsbeschränkungen (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**). |
| AllowXmlAttributes | 16 | Erlaube xml:*‑Attribute, selbst wenn sie im Schema nicht definiert sind. Die Attribute werden basierend auf ihrem Datentyp validiert. |

## Siehe auch

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
