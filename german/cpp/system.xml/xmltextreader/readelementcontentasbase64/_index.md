---
title: "System::Xml::XmlTextReader::ReadElementContentAsBase64 Methode"
linktitle: "ReadElementContentAsBase64"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlTextReader::ReadElementContentAsBase64 Methode. Liest das Element und dekodiert den Base64-Inhalt in C++."
type: docs
weight: 4900
url: /de/cpp/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64 method


Liest das Element und dekodiert den Base64‑Inhalt.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | ArrayPtr\<uint8_t\> | Der Puffer, in den der resultierende Text kopiert werden soll. Dieser Wert darf nicht **nullptr** sein. |
| Index | int32_t | Der Versatz im Puffer, ab dem das Ergebnis kopiert werden soll. |
| Anzahl | int32_t | Die maximale Anzahl von Bytes, die in den Puffer kopiert werden sollen. Die tatsächlich kopierte Anzahl von Bytes wird von dieser Methode zurückgegeben. |

### ReturnValue

Die Anzahl der Bytes, die in den Puffer geschrieben wurden.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
