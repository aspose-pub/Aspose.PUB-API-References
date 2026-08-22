---
title: "System::Text::ICUEncoder::GetByteCount yöntemi"
linktitle: "GetByteCount"
second_title: "Aspose.PUB için C++"
description: "System::Text::ICUEncoder::GetByteCount yöntemi. Bir tamponu kodlamak için gereken bayt sayısını C++'ta alır."
type: docs
weight: 400
url: /tr/cpp/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
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
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## ICUEncoder::GetByteCount(const char_t *, int, bool) method


Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| sayım | int | Kodlanacak karakter sayısı. |
| flush | bool | Doğruysa, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### ReturnValue

Tamponu kodlamak için gereken bayt sayısı.

## Ayrıca Bakınız

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
