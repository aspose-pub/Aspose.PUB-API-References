---
title: "System::Text::ICUDecoder::GetCharCount yöntemi"
linktitle: "GetCharCount"
second_title: "Aspose.PUB için C++"
description: "System::Text::ICUDecoder::GetCharCount yöntemi. C++'de bir tamponu çözmek için gereken karakter sayısını alır."
type: docs
weight: 400
url: /tr/cpp/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | ArrayPtr\<uint8_t\> | Çözülmesi gereken baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofseti. |
| sayım | int | Çözümlemek için bayt sayısı. |

### ReturnValue

Tamponu çözmek için gereken karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | ArrayPtr\<uint8_t\> | Çözülmesi gereken baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofseti. |
| sayım | int | Çözümlemek için bayt sayısı. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |

### ReturnValue

Tamponu çözmek için gereken karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const uint8_t * | Çözülmesi gereken baytlar. |
| sayım | int | Çözümlemek için bayt sayısı. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |

### ReturnValue

Tamponu çözmek için gereken karakter sayısı.

## Ayrıca Bakınız

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
