---
title: "System::Threading::Semaphore class"
linktitle: "Semaphore"
second_title: "Aspose.PUB für C++"
description: "System::Threading::Semaphore class. Semaphore-Implementierung. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 700
url: /de/cpp/system.threading/semaphore/
---
## Semaphore class


[Semaphore](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Release](./release/)() | Gibt die Sperre des Semaphores frei. |
| [Release](./release/)(int) | Gibt mehrere Sperren des Semaphores frei. |
| virtual [Reset](./reset/)() | Setzt das Semaphore in den nicht-signalierten Zustand. Nicht unterstützt. |
| [Semaphore](./semaphore/)(int, int) | RTTI-Informationen. |
| [Semaphore](./semaphore/)(int, int, const String\&) | Erstellt ein benanntes Semaphore. |
| [Semaphore](./semaphore/)(int, int, const String\&, bool\&) | Erstellt ein benanntes Semaphore. |
| virtual [Set](./set/)() | Setzt das Semaphore in den signalisierten Zustand. Nicht unterstützt. |
| [WaitOne](./waitone/)() override | Sperrt das Semaphore. Führt unbegrenztes Warten aus, falls erforderlich. |
| [WaitOne](./waitone/)(int) override | Sperrt das Semaphore. Führt Warten aus, falls erforderlich. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Spezialwert, der von der Funktion zurückgegeben wird, andernfalls wird der Index des signalisierten Objekts im Array zurückgegeben, wenn die Zeitüberschreitung überschritten wird und nichts signalisiert. |
## Siehe auch

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
