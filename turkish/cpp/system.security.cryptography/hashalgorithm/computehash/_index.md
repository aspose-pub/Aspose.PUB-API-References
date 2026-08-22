---
title: "System::Security::Cryptography::HashAlgorithm::ComputeHash yöntemi"
linktitle: "ComputeHash"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::HashAlgorithm::ComputeHash yöntemi. C++'ta tamponu karmalar."
type: docs
weight: 200
url: /tr/cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method


Tamponu hashler.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Kaynak tampon. |

### ReturnValue

Hesaplanan karma değeri.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method


Tampon dilimini hashler.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Kaynak tampon. |
| ofset | int | Kaynak tampondaki ofset. |
| sayım | int | Kaynak tampondan kullanılacak bayt sayısı. |

### ReturnValue

Hesaplanan karma değeri.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method


Akışı sonuna kadar okur ve okunan veri için hash hesaplar.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | SharedPtr\<IO::Stream\> const\& | Veriyi okumak için akış. |

### ReturnValue

Tüm akış verisi için hesaplanan karma değeri.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
