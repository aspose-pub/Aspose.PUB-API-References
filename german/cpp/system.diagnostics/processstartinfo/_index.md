---
title: "System::Diagnostics::ProcessStartInfo Klasse"
linktitle: "ProcessStartInfo"
second_title: "Aspose.PUB für C++"
description: "System::Diagnostics::ProcessStartInfo Klasse. Beschreibt Prozessstartparameter. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.diagnostics/processstartinfo/
---
## ProcessStartInfo class


Beschreibt Prozessstartparameter. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ProcessStartInfo : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Arguments](./get_arguments/)() const | Liest Prozessargumente. |
| [get_CreateNoWindow](./get_createnowindow/)() const | Liest NoWindow‑Eigenschaft. |
| [get_EnvironmentVariables](./get_environmentvariables/)() const | Liest Prozessumgebungsvariablen. |
| [get_FileName](./get_filename/)() const | Liest Prozessdateinamen. |
| [get_RedirectStandardError](./get_redirectstandarderror/)() const | Liest RedirectStandardError‑Eigenschaft. |
| [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Liest RedirectStandardInput‑Eigenschaft. |
| [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Liest RedirectStandardOutput‑Eigenschaft. |
| [get_UseShellExecute](./get_useshellexecute/)() const | Liest UseShellExecute‑Eigenschaft. |
| [get_WindowStyle](./get_windowstyle/)() const | Liest Fensterstil. |
| [get_WorkingDirectory](./get_workingdirectory/)() const | Liest Arbeitsverzeichnis des Prozesses. |
| [ProcessStartInfo](./processstartinfo/)() | Erstellt leeres Startinfo‑Objekt. |
| [ProcessStartInfo](./processstartinfo/)(const String\&) | Erstellt Startinfo‑Objekt. |
| [ProcessStartInfo](./processstartinfo/)(const String\&, const String\&) | Erstellt Startinfo‑Objekt. |
| [set_Arguments](./set_arguments/)(const String\&) | Setzt Prozessargumente. |
| [set_CreateNoWindow](./set_createnowindow/)(bool) | Setzt NoWindow‑Eigenschaft. |
| [set_FileName](./set_filename/)(const String\&) | Setzt Prozessdateinamen. |
| [set_RedirectStandardError](./set_redirectstandarderror/)(bool) | Setzt RedirectStandardError‑Eigenschaft. |
| [set_RedirectStandardInput](./set_redirectstandardinput/)(bool) | Setzt RedirectStandardInput‑Eigenschaft. |
| [set_RedirectStandardOutput](./set_redirectstandardoutput/)(bool) | Setzt RedirectStandardOutput‑Eigenschaft. |
| [set_UseShellExecute](./set_useshellexecute/)(bool) | Setzt UseShellExecute‑Eigenschaft. |
| [set_WindowStyle](./set_windowstyle/)(ProcessWindowStyle) | Setzt Fensterstil. |
| [set_WorkingDirectory](./set_workingdirectory/)(const String\&) | Setzt das Arbeitsverzeichnis des Prozesses. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PUB for C++](../../)
