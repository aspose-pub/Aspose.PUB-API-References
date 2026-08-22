---
title: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method"
linktitle: "Şifrele"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::Encrypt method. Girdi verilerini belirtilen dolgu modunu kullanarak C++'ta şifreler."
type: docs
weight: 400
url: /tr/cpp/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


Belirtilen dolgu modunu kullanarak giriş verilerini şifreler.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | ByteArrayPtr | Şifrelemek için [Byte](../../../system/byte/) dizisi. |
| dolgu | SharedPtr\<RSAEncryptionPadding\> | Dolgu modu. |

### ReturnValue

Şifrelenmiş veri bayt dizisi biçiminde.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


Mesajı şifreler. Henüz uygulanmadı.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb | const ByteArrayPtr\& | [Data](../../../system.data/) şifrelemek için. |
| use_oaep | bool | OAEP dolgu kullanmak için true, PKCS#1 v1.5 dolgu kullanmak için false. |

### ReturnValue

Şifrelenmiş veri dizisi.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
