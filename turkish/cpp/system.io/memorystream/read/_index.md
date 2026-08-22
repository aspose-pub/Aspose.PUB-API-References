---
title: "System::IO::MemoryStream::Read metodu"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::MemoryStream::Read metodu. Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine C++'ta yazar."
type: docs
weight: 1100
url: /tr/cpp/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Okunan baytların yazılacağı bayt dizisi |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytları yazmak için bayt dizisi görünümü |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
