---
title: "Namespace System::Net::Security"
linktitle: "System::Net::Security"
second_title: "Aspose.PUB für C++"
description: "Wie man den Namespace System::Net::Security in C++ verwendet."
type: docs
weight: 3100
url: /de/cpp/system.net.security/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Enthält die Methoden zum Weitergeben von Anmeldeinformationen über einen Stream. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SslStream](./sslstream/) | Ein Stream, der das SSL-Protokoll verwendet, um den Server und optional den Client zu authentifizieren. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-spezifische Authentifizierungsflags. |
| [EncryptionPolicy](./encryptionpolicy/) | Enumeriert die Verschlüsselungsrichtlinien. |
| [SslPolicyErrors](./sslpolicyerrors/) | Enumeriert die Richtlinienfehler von SSL. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Ein Benutzer-Delegat, das zum Auswählen des lokalen SSL-Zertifikats verwendet wird. |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Ein Benutzer-Delegat, das zum Verifizieren des entfernten SSL-Zertifikats verwendet wird. |
