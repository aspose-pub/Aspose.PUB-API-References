---
title: "System::Text::EncoderFallbackBuffer::Fallback yöntemi"
linktitle: "Geri dönüş"
second_title: "Aspose.PUB için C++"
description: "System::Text::EncoderFallbackBuffer::Fallback yöntemi. C++'de gerçek geri dönüş prosedürünü uygular."
type: docs
weight: 100
url: /tr/cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknown | char_t | Karakter kodlayıcı kodlamada başarısız olur. |
| indeks | int | Hata oluşturan karakterin indeksi. |

### ReturnValue

Tampon bilinmeyen karakterleri işliyorsa doğru, yok sayıyorsa yanlış.

## Ayrıca Bakınız

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| charUnknownHigh | char_t | Hata oluşturan yedek çiftin yüksek kısmı. |
| charUnknownLow | char_t | Hata oluşturan yedek çiftin düşük kısmı. |
| indeks | int | Hata oluşturan karakterin indeksi. |

### ReturnValue

Tampon bilinmeyen karakterleri işliyorsa doğru, yok sayıyorsa yanlış.

## Ayrıca Bakınız

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
