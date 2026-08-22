---
title: "System::Text::Decoder::Convert yöntemi"
linktitle: "Dönüştür"
second_title: "Aspose.PUB için C++"
description: "System::Text::Decoder::Convert yöntemi. Baytları C++'ta karakterlere dönüştürür."
type: docs
weight: 100
url: /tr/cpp/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Baytları karakterlere dönüştürür.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | ArrayPtr\<uint8_t\> | Çözülmesi gereken baytlar. |
| byteIndex | int | Giriş tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | ArrayPtr\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |
| charCount | int | Hedef dizi boyutu. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını depolamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını depolamak için değişkene referans. |
| completed | bool\& | Girdi tamponu tükendiğinde doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Baytları karakterlere dönüştürür.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const uint8_t * | Çözülmesi gereken baytlar. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |
| bytesUsed | int\& | Okunan bayt sayısını depolamak için değişkene referans. |
| charsUsed | int\& | Yazılan karakter sayısını depolamak için değişkene referans. |
| completed | bool\& | Girdi tamponu tükendiğinde doğru, aksi takdirde yanlış olarak ayarlanacak değişkene referans. |

## Ayrıca Bakınız

* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
