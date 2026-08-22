---
title: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature yöntemi"
linktitle: "VerifySignature"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature yöntemi. Veri karmasının imzasını C++'de doğrular."
type: docs
weight: 400
url: /tr/cpp/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature method


Veri karmasının imzasını doğrular.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbHash | System::ArrayPtr\<uint8_t\> | Veri için hesaplanan karma. |
| rgbSignature | System::ArrayPtr\<uint8_t\> | Veri için alınan imza. |

### ReturnValue

İmza geçerli ise true, aksi takdirde false.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RSAPKCS1SignatureDeformatter](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
