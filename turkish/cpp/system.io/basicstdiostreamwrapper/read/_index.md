---
title: "System::IO::BasicSTDIOStreamWrapper::Read yöntemi"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSTDIOStreamWrapper::Read yöntemi. Sarma modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okur ve uint8_t türüne dönüştürür. Okumanın sonucunu C++'ta belirtilen bayt dizisine yazar."
type: docs
weight: 400
url: /tr/cpp/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Eğer sarmalama modu ikili ise, belirtilen sayıda baytı akıştan okur, aksi takdirde belirtilen sayıda karakteri okur ve uint8_t tipine dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Okunan baytların yazılacağı bayt dizisi |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt veya karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytları yazmak için bayt dizisi görünümü |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
