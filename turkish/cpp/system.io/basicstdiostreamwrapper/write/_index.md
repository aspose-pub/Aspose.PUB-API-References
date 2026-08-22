---
title: "System::IO::BasicSTDIOStreamWrapper::Write yöntemi"
linktitle: "Yaz"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSTDIOStreamWrapper::Write yöntemi. Sarma modu ikili ise, belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar; aksi takdirde belirtilen bayt dizisinden belirtilen alt aralığı char_type türüne dönüştürür ve ardından sonucu akışa yazar C++'ta."
type: docs
weight: 700
url: /tr/cpp/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Eğer sarmalama modu ikili ise, akışa belirtilen bayt dizisinden belirtilen bayt alt aralığını yazar, aksi takdirde belirtilen bayt dizisindeki belirtilen bayt alt aralığını char_type tipine dönüştürür ve ardından sonucu akışa yazar.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Yazılacak baytları içeren dizi |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki 0 tabanlı bir indeks |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Yazılacak baytları içeren dizi görünümü |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki öğenin 0 tabanlı indeksi |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı |

## Ayrıca Bakınız

* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
