---
title: "System::Xml::WriteState enum"
linktitle: "WriteState"
second_title: "Aspose.PUB für C++"
description: "System::Xml::WriteState enum. Gibt den Zustand des XmlWriter in C++ an."
type: docs
weight: 5700
url: /de/cpp/system.xml/writestate/
---
## WriteState enum


Gibt den Zustand des [XmlWriter](../xmlwriter/) an.

```cpp
enum class WriteState
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Start | 0 | Zeigt an, dass die XmlWriter::Write‑Methode noch nicht aufgerufen wurde. |
| Prolog | 1 | Zeigt an, dass das Prolog geschrieben wird. |
| Element | 2 | Gibt an, dass ein Element-Start-Tag geschrieben wird. |
| Attribute | 3 | Gibt an, dass ein Attributwert geschrieben wird. |
| Inhalt | 4 | Gibt an, dass Elementinhalt geschrieben wird. |
| Closed | 5 | Gibt an, dass die Methode [XmlWriter::Close](../xmlwriter/close/) aufgerufen wurde. |
| Error | 6 | Eine Ausnahme wurde ausgelöst, die den [XmlWriter](../xmlwriter/) in einen ungültigen Zustand versetzt hat. Sie können die Methode [XmlWriter::Close](../xmlwriter/close/) aufrufen, um den [XmlWriter](../xmlwriter/) in den Zustand [WriteState::Closed](./) zu versetzen. Jeder andere Aufruf einer [XmlWriter](../xmlwriter/) Methode führt zu einer InvalidOperationException. |

## Siehe auch

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
