---
title: "Namespace System::Threading"
linktitle: "System::Threading"
second_title: "Aspose.PUB für C++"
description: "Wie man das Namespace System::Threading in C++ verwendet."
type: docs
weight: 4900
url: /de/cpp/system.threading/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Ereignis, um einen wartenden Thread zu benachrichtigen, das automatisch zurückgesetzt wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [EventWaitHandle](./eventwaithandle/) | Ereignis, das an einen wartenden Thread gesendet werden kann. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Interlocked](./interlocked/) | Stellt eine API für thread-sichere Operationen bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [ManualResetEvent](./manualresetevent/) | Ereignis, um einen wartenden Thread zu benachrichtigen, das nicht automatisch zurückgesetzt wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Monitor](./monitor/) | Klasse [Monitor](./monitor/) bietet einen Mechanismus, der den Zugriff auf Objekte synchronisiert. |
| [Mutex](./mutex/) | Implementierung von [Mutex](./mutex/). Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Semaphore](./semaphore/) | Implementierung von [Semaphore](./semaphore/). Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Thread](./thread/) | Implementierung von [Thread](./thread/). Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) Pool-API, die das Einreihen von Jobs in die Warteschlange ermöglicht, die von einem Pool von Arbeiter-Threads gelesen werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) Pool interne Daten. Dies ist ein Singleton‑Typ mit Speicherverwaltung, die über Zugriffs‑Funktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen. |
| [Timer](./timer/) | [Timer](./timer/) Klasse, die ein Job‑Element nach einer Verzögerung in einem separaten Thread ausführt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [TimerQueue](./timerqueue/) | Warteschlange, die [Timer](./timer/)‑Objekte verwaltet. Dies ist lediglich eine Implementierung. [Timer](./timer/)‑Objekte registrieren sich dort selbst, Sie müssen dies nicht tun, um sie zu verwenden – verwenden Sie stattdessen die [Timer](./timer/) Klassen‑API. Dies ist ein Singleton‑Typ mit Speicherverwaltung, die über Zugriffs‑Funktion(en) erfolgt. Sie sollten niemals Instanzen davon direkt erstellen. |
| [WaitHandle](./waithandle/) | Warte‑Primitive Basisklasse. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Setzt den Apartment‑Zustand des Threads. |
| [EventResetMode](./eventresetmode/) | Gibt an, wie der Ereignis‑Zustand zurückgesetzt wird. |
| [ThreadState](./threadstate/) | Zustand des Threads. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) Funktion mit einem Parameter. |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ThreadStart](./threadstart/) | [Thread](./thread/) Funktion ohne Parameter. |
| [TimerCallback](./timercallback/) | Rückruffunktion, die vom Timer aufgerufen wird. |
| [wait_handle_t](./wait_handle_t/) | Handle‑Typ. |
| [WaitCallback](./waitcallback/) | Rückruffunktionseintrag, der ausgeführt wird, sobald ein Platz frei ist. |
