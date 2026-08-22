---
title: "System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature yöntemi"
linktitle: "CreateSignature"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature yöntemi. C++'ta RTTI bilgisi."
type: docs
weight: 100
url: /tr/cpp/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method


RTTI bilgisi.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) hash hesaplamak için. |

### ReturnValue

Byte dizisi biçiminde hesaplanan imza.
## Açıklamalar


Belirtilen veri için imzayı oluşturur.
## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method


Belirtilen hash değeri için imzayı oluşturur.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karma | System::SharedPtr\<HashAlgorithm\> | İmza oluştururken kullanılacak hash algoritması. |

### ReturnValue

Byte dizisi biçiminde hesaplanan imza.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Class [AsymmetricSignatureFormatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
