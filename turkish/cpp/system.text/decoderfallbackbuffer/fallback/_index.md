---
title: "System::Text::DecoderFallbackBuffer::Fallback yöntemi"
linktitle: "Geri dönüş"
second_title: "Aspose.PUB için C++"
description: "System::Text::DecoderFallbackBuffer::Fallback yöntemi. C++'de gerçek yedekleme prosedürünü uygular."
type: docs
weight: 100
url: /tr/cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback method


Gerçek geri dönüş prosedürünü uygular.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytesUnknown | ArrayPtr\<uint8_t\> | [Array](../../../system/array/) baytların, kod çözücünün çözemediği baytı da içerir. |
| indeks | int | Hata oluşturan baytın indeksi. |

### ReturnValue

Tampon bilinmeyen baytları işliyorsa doğru, yok sayıyorsa yanlış.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
