---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method"
linktitle: "VerifyData"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method. C++'de veri imzasını kontrol eder."
type: docs
weight: 1700
url: /tr/cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Veri imzasını kontrol eder.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) imza kontrolü için. |
| imza | const ByteArrayPtr\& | Alındığı gibi imza. |

### ReturnValue

İmza geçerli ise true, aksi takdirde false.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | const ByteArrayPtr\& | İmzalanmış veri. |
| imza | const ByteArrayPtr\& | İmza verisi. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | const ByteArrayPtr\& | İmzalanmış veri. |
| ofset | int32_t | Ofset **data** içinde. |
| sayım | int32_t | Hashlenecek bayt sayısı. |
| imza | const ByteArrayPtr\& | İmza verisi. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Belirtilen ikili akışın imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const StreamPtr\& | İmzalanmış veri. |
| imza | const ByteArrayPtr\& | İmza verisi. |
| hash_algorithm | const HashAlgorithmName\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## Ayrıca Bakınız

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
