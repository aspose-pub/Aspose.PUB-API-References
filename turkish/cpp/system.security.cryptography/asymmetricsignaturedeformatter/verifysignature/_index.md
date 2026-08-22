---
title: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method"
linktitle: "VerifySignature"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature method. C++'da veriler üzerindeki imzayı doğrular."
type: docs
weight: 300
url: /tr/cpp/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Veri üzerindeki imzayı doğrular.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | [Data](../../../system.data/) **rgbSignature** ile imzalanmış. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Veri için doğrulanacak imza. |

### ReturnValue

İmza kontrolü başarılıysa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method


Veri üzerindeki imzayı doğrular. Henüz uygulanmadı.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karma | System::SharedPtr\<HashAlgorithm\> | Hashleme için kullanılacak algoritma. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Veri için doğrulanacak imza. |

### ReturnValue

İmza kontrolü başarılıysa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../../hashalgorithm/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
