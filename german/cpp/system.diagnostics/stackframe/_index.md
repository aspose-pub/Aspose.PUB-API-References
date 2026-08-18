---
title: "System::Diagnostics::StackFrame Klasse"
linktitle: "StackFrame"
second_title: "Aspose.PUB für C++"
description: "System::Diagnostics::StackFrame Klasse. Gibt Informationen zu einem einzelnen Stack-Frame zurück. Nur MSVS. Objekte dieser Klasse sollten ausschließlich über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 500
url: /de/cpp/system.diagnostics/stackframe/
---
## StackFrame class


Gibt Informationen zu einem einzelnen Stack-Frame zurück. Nur MSVS. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class StackFrame : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [GetFileColumnNumber](./getfilecolumnnumber/)() | Liest die Spaltennummer. |
| virtual [GetFileLineNumber](./getfilelinenumber/)() | Liest die Zeilennummer. |
| virtual [GetFileName](./getfilename/)() | Liest den Dateinamen. |
| [GetMethod](./getmethod/)() | Liest Methodeninformationen. |
| [operator=](./operator=/)(const StackFrame\&) const | Keine Änderung. |
| [StackFrame](./stackframe/)(int) | Erstellt einen Stack-Frame am aktuellen Stack-Offset. |
| [StackFrame](./stackframe/)(const StackFrame\&) | Kein Kopieren. |
| virtual [~StackFrame](./~stackframe/)() | Destruktor. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
