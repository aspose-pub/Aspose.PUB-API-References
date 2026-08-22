---
title: "System::IO::UnmanagedMemoryStream::Read metodu"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::UnmanagedMemoryStream::Read metodu. Belirtilen sayıda baytı akıştan okuyarak C++'ta belirtilen bayt dizisine yazar."
type: docs
weight: 1000
url: /tr/cpp/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
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
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytları yazmak için bayt dizisi görünümü |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
