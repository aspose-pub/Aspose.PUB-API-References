---
title: "System::IO::Stream::Write metodu"
linktitle: "Yaz"
second_title: "Aspose.PUB için C++"
description: "System::IO::Stream::Write metodu. Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa C++'ta yazar."
type: docs
weight: 2400
url: /tr/cpp/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Yazılacak baytları içeren dizi |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki öğenin 0 tabanlı indeksi |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Yazılacak baytları içeren dizi görünümü |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki öğenin 0 tabanlı indeksi |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı |

## Ayrıca Bakınız

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parametre | Açıklama |
| --- | --- |
| N | Yığın dizisinin boyutu |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::StackArray\<uint8_t, N\>\& | Yazılacak baytları içeren yığın dizisi |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki öğenin 0 tabanlı indeksi |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı |

## Ayrıca Bakınız

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
