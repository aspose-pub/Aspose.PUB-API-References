---
title: "System::Text::RegularExpressions::Group class"
linktitle: "Group"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::Group class. Ergebnis einer Übereinstimmung, die durch eine einzelne Erfassungsgruppe durchgeführt wurde. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.text.regularexpressions/group/
---
## Group class


Ergebnis einer Übereinstimmung, die durch eine einzelne Erfassungsgruppe durchgeführt wurde. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Fügt eine Erfassung zur Gruppe hinzu. |
| [get_Captures](./get_captures/)() | Liefert verfügbare Erfassungen. |
| [get_Success](./get_success/)() | Prüft, ob die Erfassung für diese Gruppe erfolgreich war. |
| [Group](./group/)(const UStringPtr\&, int, int) | Konstruktor. |
| [Group](./group/)() | Konstruktor einer leeren Gruppe. |
## Siehe auch

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
