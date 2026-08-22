---
title: "System::IO::MemoryStream::MemoryStream yapıcı"
linktitle: "MemoryStream"
second_title: "Aspose.PUB için C++"
description: "System::IO::MemoryStream::MemoryStream yapıcı. C++'ta başlangıç kapasitesi 0 olan yeni bir MemoryStream sınıfı örneği oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructor


Başlangıç kapasitesi 0 olan yeni bir [MemoryStream](../) sınıfı örneği oluşturur.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## Ayrıca Bakınız

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructor


Belirtilen bellek tamponuna bağlı bir bellek akışı temsil eden yeni bir [MemoryStream](../) sınıfı örneği oluşturur. Bir parametre akışın yazılabilir olup olmadığını belirtir.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=true)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| içerik | const ArrayPtr\<uint8_t\>\& | Oluşturulan nesne tarafından temsil edilen akışın temel alacağı bir bellek tamponu olarak kullanılacak bayt dizisi |
| yazılabilir | bool | Akışın yazılabilir olup olması gerektiğini belirtir |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructor


Belirtilen indeksten başlayan ve belirtilen öğe sayısını içeren, belirtilen bellek tamponunun bir segmentine bağlı bir bellek akışı temsil eden yeni bir [MemoryStream](../) sınıfı örneği oluşturur. Parametreler akışın yazılabilir olup olmadığını ve GetBytes() yönteminin çağrılıp çağrılamayacağını belirtir.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=true, bool publiclyVisible=false)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| içerik | const ArrayPtr\<uint8_t\>\& | Oluşturulan nesne tarafından temsil edilen akışın temel alacağı bir bellek tamponu olarak kullanılacak, bir segmenti kullanılacak bayt dizisi |
| indeks | int | **content** içinde segmentin başladığı öğenin 0 tabanlı indeksi |
| sayım | int | Segmentte dahil edilen **content** öğelerinin sayısı |
| yazılabilir | bool | Akışın yazılabilir olup olması gerektiğini belirtir |
| publiclyVisible | bool | Temel bellek tamponunun GetByte() yöntemi çağıranına sunulup sunulmayacağını belirtir |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## MemoryStream::MemoryStream(int) constructor


Belirtilen boyutta bir bellek tamponuna dayalı bir akışı temsil eden yeni bir [MemoryStream](../) sınıfı örneği oluşturur.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| capacity_ | int | Oluşturulan nesne tarafından temsil edilen akışa bağlı bir bellek tamponunun bayt cinsinden boyutu |

## Ayrıca Bakınız

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
