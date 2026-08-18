---
title: "System::ComponentModel::BackgroundWorker Klasse"
linktitle: "BackgroundWorker"
second_title: "Aspose.PUB für C++"
description: "System::ComponentModel::BackgroundWorker Klasse. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | RTTI-Informationen. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Ermittelt einen Wert, der angibt, ob der [System::ComponentModel::BackgroundWorker](./) Fortschrittsaktualisierungen melden kann. |
| [ReportProgress](./reportprogress/)(int) | Löst das Ereignis **System::ComponentModel::BackgroundWorker::ProgressChanged** aus. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Löst das Ereignis **System::ComponentModel::BackgroundWorker::ProgressChanged** mit einem userState-Objekt aus. |
| [RunWorkerAsync](./runworkerasync/)() | Startet die Ausführung einer Hintergrundoperation. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Startet die Ausführung einer Hintergrundoperation. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Setzt einen Wert, der angibt, ob der [System::ComponentModel::BackgroundWorker](./) Fortschrittsaktualisierungen melden kann. |
| [~BackgroundWorker](./~backgroundworker/)() | Destruktor. |
## Siehe auch

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
