---
title: "System::Threading::WaitHandle Klasse"
linktitle: "WaitHandle"
second_title: "Aspose.PUB für C++"
description: "System::Threading::WaitHandle Klasse. Basis‑Klasse für Warte‑Primitive. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1300
url: /de/cpp/system.threading/waithandle/
---
## WaitHandle class


Basis‑Klasse für Warte‑Primitive. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class WaitHandle : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Close](./close/)() | Gibt alle mit dem Handle verbundenen Ressourcen frei. |
| [get_Handle](./get_handle/)() | Liefert das Handle. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | RTTI-Informationen. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Wartet, bis alle Handles ausgelöst wurden. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Wartet, bis alle Handles ausgelöst wurden. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Wartet, bis einer der Handles ausgelöst wird. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Wartet, bis einer der Handles ausgelöst wird. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Wartet, bis einer der Handles ausgelöst wird. |
| virtual [WaitOne](./waitone/)() | Wartet unbegrenzt, bis das Handle ausgelöst wird. |
| virtual [WaitOne](./waitone/)(int) | Wartet, bis das Handle ausgelöst wird. |
| virtual [WaitOne](./waitone/)(TimeSpan) | Wartet, bis das Handle ausgelöst wird. |
| virtual [WaitOne](./waitone/)(int, bool) | Wartet, bis das Handle ausgelöst wird. |
| virtual [~WaitHandle](./~waithandle/)() | Destruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Spezialwert, der von der Funktion zurückgegeben wird, andernfalls wird der Index des signalisierten Objekts im Array zurückgegeben, wenn die Zeitüberschreitung überschritten wird und nichts signalisiert. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
