---
title: "System::Security::Cryptography::DSA::SignData metodu"
linktitle: "SignData"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::DSA::SignData metodu. Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu C++'ta imzalar."
type: docs
weight: 500
url: /tr/cpp/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | const ByteArrayPtr\& | Girdi veri dizisi. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. Girdi verisi için [DSA](../) imzasını döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | const ByteArrayPtr\& | Girdi veri dizisi. |
| ofset | int32_t | Ofset **data** içinde. |
| sayım | int32_t | Girdi verisi olarak kullanılacak bayt sayısı. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. Girdi verisi için [DSA](../) imzasını döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Belirtilen ikili akışın hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const StreamPtr\& | İkili akış. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. Girdi verisi için [DSA](../) imzasını döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
