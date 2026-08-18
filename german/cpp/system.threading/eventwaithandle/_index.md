---
title: "System::Threading::EventWaitHandle-Klasse"
linktitle: "EventWaitHandle"
second_title: "Aspose.PUB für C++"
description: "System::Threading::EventWaitHandle-Klasse. Ereignis, das an einen wartenden Thread gesendet werden kann. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


Ereignis, das an einen wartenden Thread gesendet werden kann. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | RTTI-Informationen. |
| virtual [Reset](./reset/)() | Setzt das Ereignis in den nicht-signalisierenden Zustand. |
| virtual [Set](./set/)() | Setzt das Ereignis in den signalisierenden Zustand. |
| [~EventWaitHandle](./~eventwaithandle/)() | Destruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Spezialwert, der von der Funktion zurückgegeben wird, andernfalls wird der Index des signalisierten Objekts im Array zurückgegeben, wenn die Zeitüberschreitung überschritten wird und nichts signalisiert. |
## Siehe auch

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
