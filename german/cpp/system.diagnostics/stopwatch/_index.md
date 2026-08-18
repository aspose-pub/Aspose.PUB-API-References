---
title: "System::Diagnostics::Stopwatch Klasse"
linktitle: "Stopwatch"
second_title: "Aspose.PUB für C++"
description: "System::Diagnostics::Stopwatch Klasse. Ermöglicht Zeitmessung. Objekte dieser Klasse sollten ausschließlich über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 700
url: /de/cpp/system.diagnostics/stopwatch/
---
## Stopwatch class


Ermöglicht Zeitmessung. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Stopwatch : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Elapsed](./get_elapsed/)() const | Liest die gesamte verstrichene Zeit, die von der aktuellen Instanz gemessen wurde. |
| [get_ElapsedMilliseconds](./get_elapsedmilliseconds/)() const | Liest die gesamte verstrichene Zeit, die von der aktuellen Instanz gemessen wurde, in Millisekunden. |
| [get_ElapsedTicks](./get_elapsedticks/)() const | Ermittelt die insgesamt vergangene Zeit, die von der aktuellen Instanz gemessen wurde, in Timer‑Ticks. |
| [get_IsRunning](./get_isrunning/)() const | Überprüft, ob die Stoppuhr läuft. |
| [Reset](./reset/)() | Stoppt die Zeitmessung, setzt das gemessene Intervall auf Null. |
| [Restart](./restart/)() | Setzt das gemessene Intervall auf Null und startet anschließend die Zeitmessung. |
| [Start](./start/)() | Startet die Zeitmessung. |
| static [StartNew](./startnew/)() | Erstellt ein neues [Stopwatch](./)-Objekt und startet die Messung. |
| [Stop](./stop/)() | Stoppt die Zeitmessung. |
| [Stopwatch](./stopwatch/)() | RTTI-Informationen. |
| virtual [~Stopwatch](./~stopwatch/)() | Destruktor. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
