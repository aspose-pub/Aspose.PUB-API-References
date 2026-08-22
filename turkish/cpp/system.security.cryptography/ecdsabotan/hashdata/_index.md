---
title: "System::Security::Cryptography::ECDsaBotan::HashData yöntemi"
linktitle: "HashData"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::ECDsaBotan::HashData yöntemi. C++'da belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar."
type: docs
weight: 700
url: /tr/cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Belirtilen veri dizisinin karma değerini belirtilen karma algoritmasıyla hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | ByteArrayPtr | Hashlamak için [Data](../../../system.data/). |
| ofset | int32_t | Ofset **data** içinde. |
| sayım | int32_t | Hashlenecek bayt sayısı. |
| hash_algorithm | HashAlgorithmName | Hash algoritması. |

### ReturnValue

Hashlenmiş veri.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Belirtilen ikili akışın karma değerini belirtilen karma algoritmasıyla hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | StreamPtr | İkili akış hash'lenmiş. |
| hash_algorithm | HashAlgorithmName | Hash algoritması. |

### ReturnValue

Hashlenmiş veri.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
