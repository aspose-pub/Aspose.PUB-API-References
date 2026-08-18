---
title: "System::IAsyncResult‑Klasse"
linktitle: "IAsyncResult"
second_title: "Aspose.PUB für C++"
description: "System::IAsyncResult Klasse. Stellt den Status einer asynchronen Operation dar. Objekte dieser Klasse sollten nur über die System::MakeObject() Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3100
url: /de/cpp/system/iasyncresult/
---
## IAsyncResult class


Stellt den Status einer asynchronen Operation dar. Objekte dieser Klasse sollten nur über die [System::MakeObject()](../makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class IAsyncResult : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [get_AsyncState](./get_asyncstate/)() | Gibt ein Objekt zurück, das die Informationen über den asynchronen Vorgang enthält. |
| virtual [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Gibt eine Instanz von WaitHandle zurück, die verwendet werden kann, um auf den Abschluss des asynchronen Vorgangs zu warten. |
| virtual [get_CompletedSynchronously](./get_completedsynchronously/)() | Gibt einen Wert zurück, der angibt, ob der asynchrone Vorgang synchron abgeschlossen wurde. |
| virtual [get_IsCompleted](./get_iscompleted/)() | Gibt einen Wert zurück, der angibt, ob der asynchrone Vorgang abgeschlossen ist. |
| virtual [~IAsyncResult](./~iasyncresult/)() | Destruktor. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Gemeinsamer Zeiger auf [IAsyncResult](./). |
## Siehe auch

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
