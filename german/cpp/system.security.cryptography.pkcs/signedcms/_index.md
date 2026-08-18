---
title: "System::Security::Cryptography::Pkcs::SignedCms Klasse"
linktitle: "SignedCms"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::Pkcs::SignedCms Klasse. Signiert Inhalte gemäß dem CMS/PKCS #7‑Standard. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.security.cryptography.pkcs/signedcms/
---
## SignedCms class


Kennzeichnet den Inhalt gemäß CMS/PKCS #7-Standard. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SignedCms : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ComputeSignature](./computesignature/)(const SharedPtr\<CmsSigner\>\&, bool) | Erstellt eine Signatur. |
| [Encode](./encode/)() | Kodiert CMS/PKCS #7-Nachricht. |
| [SignedCms](./signedcms/)(const SharedPtr\<ContentInfo\>\&, bool) | Konstruktor. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PUB for C++](../../)
