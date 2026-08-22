---
title: "System::Security::Cryptography::RSACryptoServiceProvider::SignData method"
linktitle: "SignData"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RSACryptoServiceProvider::SignData method. Belirtilen girdi değerinin imzasını C++'ta hesaplar."
type: docs
weight: 1600
url: /tr/cpp/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | Giriş verilerini okumak için [Buffer](../../../system/buffer/). |
| halg | const SharedPtr\<Object\>\& | Kullanılacak hash algoritması. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | Giriş verilerini okumak için [Buffer](../../../system/buffer/). |
| ofset | int32_t | Giriş tamponu diliminin başlangıç indeksi. |
| sayım | int32_t | Giriş tamponu diliminin boyutu. |
| halg | const SharedPtr\<Object\>\& | Kullanılacak hash algoritması. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Belirtilen giriş değerinin imzasını hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_stream | const SharedPtr\<IO::Stream\>\& | İmzalanan verileri okumak için akış. |
| halg | const SharedPtr\<Object\>\& | Kullanılacak hash algoritması. |

### ReturnValue

[RSA](../../rsa/) signature for specified data.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
