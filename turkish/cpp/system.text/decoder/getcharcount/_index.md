---
title: "System::Text::Decoder::GetCharCount yöntemi"
linktitle: "GetCharCount"
second_title: "Aspose.PUB için C++"
description: "System::Text::Decoder::GetCharCount yöntemi. Bir tamponu çözümlemek için gereken karakter sayısını C++'ta alır."
type: docs
weight: 400
url: /tr/cpp/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
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
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
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
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Decoder::GetCharCount(const uint8_t *, int, bool) method


Bir tamponu kodlamak için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const uint8_t * | Çözülmesi gereken baytlar. |
| sayım | int | Çözümlemek için bayt sayısı. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |

### ReturnValue

Tamponu çözmek için gereken karakter sayısı.

## Ayrıca Bakınız

* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
