---
title: "System::IO::Stream::Read metodu"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::Stream::Read yöntemi. Belirtilen sayıda baytı akıştan okur ve C++'ta belirtilen bayt dizisine yazar."
type: docs
weight: 1700
url: /tr/cpp/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
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
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Okunan baytları yazmak için bayt dizisi görünümü |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parametre | Açıklama |
| --- | --- |
| N | Yığın dizisinin boyutu |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::StackArray\<uint8_t, N\>\& | Okunan baytların yazılacağı bayt yığını dizisi |
| ofset | int32_t | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| sayım | int32_t | Okunacak bayt sayısı |

### ReturnValue

Okunan bayt sayısı

## Ayrıca Bakınız

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
