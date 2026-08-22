---
title: "System::Text::Encoder::GetByteCount metodu"
linktitle: "GetByteCount"
second_title: "Aspose.PUB için C++"
description: "System::Text::Encoder::GetByteCount metodu. C++'de bir tamponu kodlamak için gereken bayt sayısını alır."
type: docs
weight: 400
url: /tr/cpp/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Kodlanacak karakterler. |
| index | int | [Buffer](../../../system/buffer/) ofseti. |
| sayım | int | Kodlanacak karakter sayısı. |
| flush | bool | Doğruysa, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### ReturnValue

Tamponu kodlamak için gereken bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Encoder::GetByteCount(const char_t *, int, bool) method


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| sayım | int | Kodlanacak karakter sayısı. |
| flush | bool | Doğruysa, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### ReturnValue

Tamponu kodlamak için gereken bayt sayısı.

## Ayrıca Bakınız

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
