---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt-Methode"
linktitle: "Decrypt"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt-Methode. Entschlüsselt Eingabedaten mit dem angegebenen Auffüllmodus in C++."
type: docs
weight: 200
url: /de/cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Entschlüsselt Eingabedaten unter Verwendung des angegebenen Auffüllmodus.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) Array zum Entschlüsseln. |
| Auffüllung | SharedPtr\<RSAEncryptionPadding\> | Padding-Modus. |

### ReturnValue

Entschlüsselte Daten im Byte-Array-Format.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Entschlüsselt Nachricht. Nicht implementiert.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) zum Entschlüsseln. |
| use_oaep | bool | True, um OAEP-Auffüllung zu verwenden, false, um PKCS#1 v1.5-Auffüllung zu verwenden. |

### ReturnValue

Entschlüsseltes Datenarray.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
