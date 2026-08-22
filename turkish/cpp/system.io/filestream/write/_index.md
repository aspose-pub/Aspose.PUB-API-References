---
title: "System::IO::FileStream::Write yöntemi"
linktitle: "Yaz"
second_title: "Aspose.PUB için C++"
description: "System::IO::FileStream::Write yöntemi. Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa C++'ta yazar."
type: docs
weight: 1700
url: /tr/cpp/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const ArrayPtr\<uint8_t\>\& | Yazılacak baytları içeren dizi. |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki 0 tabanlı bir indeks. |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | const System::Details::ArrayView\<uint8_t\>\& | Yazılacak baytları içeren dizi görünümü. |
| ofset | int32_t | Yazılacak alt aralığın başladığı **buffer** içindeki 0 tabanlı bir indeks. |
| sayım | int32_t | Yazılacak alt aralıktaki öğe sayısı. |

## Ayrıca Bakınız

* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
