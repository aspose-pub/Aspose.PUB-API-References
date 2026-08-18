---
title: "System::Security Namensraum"
linktitle: "System::Security"
second_title: "Aspose.PUB für C++"
description: "Wie man den System::Security Namensraum in C++ verwendet."
type: docs
weight: 3800
url: /de/cpp/system.security/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [SecureString](./securestring/) | Secure string, stellt Text dar, der vertraulich gehalten werden sollte. Diese Klasse verschlüsselt die internen Daten NICHT. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SecureStringMarshal](./securestringmarshal/) | Sammlung von Methoden zum Allozieren und Kopieren von nicht verwalteten Speicherblöcken. |
| [SecurityElement](./securityelement/) | XML-Objektmodell für die Kodierung von Sicherheitsobjekten. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) Zeigertyp. |
