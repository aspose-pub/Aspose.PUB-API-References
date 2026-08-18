---
title: "System::Security::Cryptography::Pkcs::CmsSigner Klasse"
linktitle: "CmsSigner"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::Pkcs::CmsSigner Klasse. Stellt eine API zum Signieren von Objekten mit CMS bereit. Signiert Objekte nicht selbst, verwenden Sie die Klasse SignedCMS, um dies zu tun. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.security.cryptography.pkcs/cmssigner/
---
## CmsSigner class


Bietet eine API zum Signieren von Objekten mit CMS. Signiert Objekte nicht selbst, verwenden Sie die Klasse SignedCMS, um dies zu tun. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class CmsSigner : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CmsSigner](./cmssigner/)(const SharedPtr\<X509Certificates::X509Certificate2\>\&) | Initialisiert den Signierer mit einem X509‑Zertifikat. |
| [get_DigestAlgorithm](./get_digestalgorithm/)() const | Ermittelt den Hash‑Algorithmus, der für die Signatur verwendet wird. |
| [get_IncludeOption](./get_includeoption/)() const | Überprüft, welche Zertifikate aus der Kette in die Signatur aufgenommen werden. |
| [set_DigestAlgorithm](./set_digestalgorithm/)(const SharedPtr\<Oid\>\&) | Legt den Hash‑Algorithmus fest, der für die Signatur verwendet wird. |
| [set_IncludeOption](./set_includeoption/)(X509Certificates::X509IncludeOption) | Gibt an, welche Zertifikate aus der Kette in die Signatur aufgenommen werden. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PUB for C++](../../)
