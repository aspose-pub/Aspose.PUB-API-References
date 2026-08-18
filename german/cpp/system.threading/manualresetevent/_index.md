---
title: "System::Threading::ManualResetEvent Klasse"
linktitle: "ManualResetEvent"
second_title: "Aspose.PUB für C++"
description: "System::Threading::ManualResetEvent Klasse. Ereignis, das wartenden Thread benachrichtigt und sich nicht automatisch zurücksetzt. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


Ereignis, das wartenden Thread benachrichtigt und sich nicht automatisch zurücksetzt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | RTTI-Informationen. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Spezialwert, der von der Funktion zurückgegeben wird, andernfalls wird der Index des signalisierten Objekts im Array zurückgegeben, wenn die Zeitüberschreitung überschritten wird und nichts signalisiert. |
## Siehe auch

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
