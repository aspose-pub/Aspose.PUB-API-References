---
title: "System::Security::SecureString class"
linktitle: "SecureString"
second_title: "Aspose.PUB für C++"
description: "System::Security::SecureString class. Sicherer String, stellt Text dar, der vertraulich zu behandeln ist. Diese Klasse VERSCHLÜSSELT DIE INTERNEN DATEN NICHT. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.security/securestring/
---
## SecureString class


Sicherer String, stellt Text dar, der vertraulich zu behandeln ist. Diese Klasse VERSCHLÜSSELN DIE INTERNEN DATEN NICHT. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SecureString : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AppendChar](./appendchar/)(char16_t) | Fügt ein Zeichen am Ende der Zeichenkette hinzu. |
| [Clear](./clear/)() | Löscht alle Zeichen aus dem aktuellen SecureString. |
| [Copy](./copy/)() const | Erstellt ein Duplikat dieses SecureString. |
| [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt genutzten Ressourcen frei. |
| [get_Length](./get_length/)() const | Ermittelt die Anzahl der Zeichen in diesem SecureString. |
| [InsertAt](./insertat/)(int32_t, char16_t) | Fügt ein Zeichen an der angegebenen Position ein. |
| [IsReadOnly](./isreadonly/)() const | Ermittelt das Flag, das angibt, ob dieses Objekt als schreibgeschützt markiert ist. |
| [MakeReadOnly](./makereadonly/)() | Macht diese sichere Zeichenkette schreibgeschützt. |
| [operator=](./operator=/)(const SecureString\&) |  |
| [RemoveAt](./removeat/)(int32_t) | Entfernt das Zeichen an der angegebenen Position. |
| [SecureString](./securestring/)() | RTTI-Informationen. |
| [SecureString](./securestring/)(const char16_t *, int32_t) | Konstruktor. |
| [SecureString](./securestring/)(const SecureString\&) |  |
| [SetAt](./setat/)(int32_t, char16_t) | Ersetzt das vorhandene Zeichen an der angegebenen Position. |
| [ToUnsecureString](./tounsecurestring/)() const | Kopiert den Inhalt dieser sicheren Zeichenkette in ein unsicheres [String](../../system/string/) Objekt. Mit Vorsicht verwenden. |
| [~SecureString](./~securestring/)() | Destruktor. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security](../)
* Library [Aspose.PUB for C++](../../)
