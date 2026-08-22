---
title: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyData metodu"
linktitle: "VerifyData"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::VerifyData metodu. C++'de veri imzasını kontrol eder."
type: docs
weight: 1800
url: /tr/cpp/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData method


Veri imzasını kontrol eder.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) imza kontrolü için. |
| halg | const SharedPtr\<Object\>\& | Kullanılacak hash algoritması. |
| imza | const ByteArrayPtr\& | Alındığı gibi imza. |

### ReturnValue

İmza geçerli ise true, aksi takdirde false.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
