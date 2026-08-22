---
title: "System::IO::BufferedStream::Read yöntemi"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::BufferedStream::Read yöntemi. Temel akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine C++'de yazar."
type: docs
weight: 900
url: /tr/cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Temel akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
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
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Temel akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytların yazılacağı bayt dizisi |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
