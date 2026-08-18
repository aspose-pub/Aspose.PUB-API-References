---
title: "System::Text::RegularExpressions::CaptureCollection Klasse"
linktitle: "CaptureCollection"
second_title: "Aspose.PUB für C++"
description: "System::Text::RegularExpressions::CaptureCollection Klasse. Liste von Captures, die von einer einzelnen Erfassungsgruppe durchgeführt werden. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.text.regularexpressions/capturecollection/
---
## CaptureCollection class


Liste von Captures, die von einer einzelnen Erfassungsgruppe durchgeführt werden. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class CaptureCollection : public System::Collections::Generic::List<CapturePtr>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Add](./add/)(const CapturePtr\&) override | Deaktiviert die Änderung der Sammlung. |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Dienstmethode zum Hinzufügen eines Captures zur Sammlung. |
| [Clear](./clear/)() override | Deaktiviert das Bereinigen der Sammlung. |
| [get_Count](./get_count/)() const override | Gibt die Anzahl der Captures zurück. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Markiert die Sammlung als schreibgeschützt. |
| [get_IsSynchronized](./get_issynchronized/)() const | Markiert die Sammlung als nicht synchronisiert. |
| [Remove](./remove/)(const CapturePtr\&) override | Deaktiviert die Änderung der Sammlung. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Base](./base/) | Basistyp. |
## Siehe auch

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
