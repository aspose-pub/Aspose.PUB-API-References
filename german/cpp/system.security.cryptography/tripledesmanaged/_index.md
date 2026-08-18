---
title: "System::Security::Cryptography::TripleDESManaged Klasse"
linktitle: "TripleDESManaged"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::TripleDESManaged Klasse. Verwaltete TripleDES‑Implementierung. Unterstützt nur die Modi ECB und CFB mit keiner Auffüllung sowie den CBC‑Modus mit keiner, Zero‑ und PKCS7‑Auffüllung. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 5200
url: /de/cpp/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged class


Verwaltete [TripleDES](../tripledes/) Implementierung. Unterstützt nur ECB- und CFB-Modi mit None-Padding und CBC-Modus mit None-, Zeros- und PKCS7-Paddings. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Erstellt ein Decryptor-Objekt mit expliziten Parametern. |
| virtual [CreateDecryptor](./createdecryptor/)() | Erstellt ein Decryptor-Objekt mit Parametern, die vom Algorithmusobjekt definiert werden. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Erstellt ein Encryptor-Objekt mit expliziten Parametern. |
| virtual [CreateEncryptor](./createencryptor/)() | Erstellt ein Encryptor-Objekt mit Parametern, die vom Algorithmusobjekt definiert werden. |
| [GenerateIV](./generateiv/)() override | Erstellt einen zufälligen Initialwert und speichert ihn in den internen Daten des Algorithmus. |
| [GenerateKey](./generatekey/)() override | Erstellt einen zufälligen Schlüssel und speichert ihn in den internen Daten des Algorithmus. |
## Siehe auch

* Class [TripleDES](../tripledes/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
