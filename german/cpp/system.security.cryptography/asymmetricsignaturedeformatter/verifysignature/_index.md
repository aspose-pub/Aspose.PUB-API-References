---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature-Methode"
linktitle: "VerifySignature"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature-Methode. Verifiziert die Signatur von Daten in C++."
type: docs
weight: 300
url: /de/cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Überprüft die Signatur der Daten.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) signiert mit **rgbSignature**. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signatur, die für Daten verifiziert werden soll. |

### ReturnValue

Wahr, wenn die Signaturprüfung erfolgreich ist, andernfalls falsch.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Überprüft die Signatur der Daten. Nicht implementiert.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Hash | System::SharedPtr\<HashAlgorithm\> | Algorithmus, der für das Hashing verwendet wird. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Signatur, die für Daten verifiziert werden soll. |

### ReturnValue

Wahr, wenn die Signaturprüfung erfolgreich ist, andernfalls falsch.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
