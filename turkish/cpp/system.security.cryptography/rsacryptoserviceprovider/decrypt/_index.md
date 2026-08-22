---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt yöntemi"
linktitle: "Decrypt"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Decrypt yöntemi. Giriş verilerini belirtilen dolgu modunu kullanarak C++'da çözer."
type: docs
weight: 200
url: /tr/cpp/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Belirtilen doldurma modunu kullanarak girdi verisini çözer.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | ByteArrayPtr | [Byte](../../../system/byte/) çözülecek dizi. |
| dolgu | SharedPtr\<RSAEncryptionPadding\> | Dolgu modu. |

### ReturnValue

Bayt dizi formatında çözülen veri.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


Mesajı çözer. Henüz uygulanmadı.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Veri](../../../system.data/) çözülecek. |
| use_oaep | bool | OAEP dolgu kullanmak için true, PKCS#1 v1.5 dolgu kullanmak için false. |

### ReturnValue

Çözülmüş veri dizisi.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
