---
title: "System::Security::Cryptography::RSA::SignHash metodu"
linktitle: "SignHash"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSA::SignHash metodu. Belirtilen hash değeri için imzayı C++'da hesaplar."
type: docs
weight: 1100
url: /tr/cpp/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash method


Belirtilen hash değeri için imzayı hesaplar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karma | ByteArrayPtr | Hash değeri. |
| hash_algorithm | HashAlgorithmName | Hash algoritması. |
| padding | SharedPtr\<RSASignaturePadding\> | Dolgu modu. Belirtilen hash için [RSA](../) imzasını döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
