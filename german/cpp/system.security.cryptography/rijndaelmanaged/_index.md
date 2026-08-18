---
title: "System::Security::Cryptography::RijndaelManaged Klasse"
linktitle: "RijndaelManaged"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::RijndaelManaged Klasse. Verwalteter Rijndael‑Algorithmus. Unterstützt nur ECB‑ und CFB‑Modi mit keinem Padding sowie CBC‑Modus mit keinem und Zero‑Padding. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben in C++."
type: docs
weight: 3100
url: /de/cpp/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged class


Verwalteter [Rijndael](../rijndael/) Algorithmus. Unterstützt nur ECB‑ und CFB‑Modi mit keinem Padding sowie CBC‑Modus mit keinem und Zero‑Padding. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in den [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
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

* Class [Rijndael](../rijndael/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
