---
title: "System::IO::FileStream::Read yöntemi"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::FileStream::Read yöntemi. Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine C++'ta yazar."
type: docs
weight: 1200
url: /tr/cpp/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Okunan baytların yazılacağı bayt dizisi. |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum. |
| sayım | int32_t | Okunacak bayt sayısı. |

### ReturnValue

Okunan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytların yazılacağı bayt dizi görünümü. |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum. |
| sayım | int32_t | Okunacak bayt sayısı. |

### ReturnValue

Okunan bayt sayısı.

## Ayrıca Bakınız

* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
