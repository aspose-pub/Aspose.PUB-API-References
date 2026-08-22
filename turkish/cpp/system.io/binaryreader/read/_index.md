---
title: "System::IO::BinaryReader::Read yöntemi"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::BinaryReader::Read yöntemi. C++'ta giriş akışından tek bir karakter okur."
type: docs
weight: 700
url: /tr/cpp/system.io/binaryreader/read/
---
## BinaryReader::Read() method


Giriş akışından tek bir karakter okur.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### ReturnValue

UTF-16 kodlamasıyla kodlanmış karakter okunur; eğer okunan karakter UTF-16 kodlamasında iki kod noktasına karşılık geliyorsa yalnızca yüksek surragate döndürülür.

## Ayrıca Bakınız

* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method


Giriş akışından belirtilen sayıda karakteri okur, UTF-16 kodlamasına dönüştürür ve ortaya çıkan UTF-16 karakterlerini belirtilen konumdan başlayarak belirtilen karakter dizisine yazar.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | ArrayPtr\<char_t\> | Giriş akışından okunan karakterlerin yazılacağı UTF-16 karakter dizisi |
| indeks | int | **buffer** içinde yazmaya başlanacak 0 tabanlı bir indeks |
| sayım | int | Akıştan okunacak karakter sayısı |

### ReturnValue

Giriş akışından okunan karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method


Giriş akışından belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | ArrayPtr\<uint8_t\> | Okunan baytların yazılacağı bayt dizisi |
| indeks | int | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
