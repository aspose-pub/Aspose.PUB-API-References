---
title: "System::Security::Cryptography::RSA::Decrypt method"
linktitle: "Decrypt"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSA::Decrypt yöntemi. Belirtilen dolgu modunu kullanarak C++'ta giriş verilerini çözer."
type: docs
weight: 100
url: /tr/cpp/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt method


Belirtilen doldurma modunu kullanarak girdi verisini çözer.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
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
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
