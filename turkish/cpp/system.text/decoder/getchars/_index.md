---
title: "System::Text::Decoder::GetChars yöntemi"
linktitle: "GetChars"
second_title: "Aspose.PUB için C++"
description: "System::Text::Decoder::GetChars yöntemi. C++'de bir tamponun kod çözülmesinden elde edilen karakterleri alır."
type: docs
weight: 500
url: /tr/cpp/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Bir tamponu kod çözümlerken elde edilen karakterleri al.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | ArrayPtr\<uint8_t\> | Çözülmesi gereken baytlar. |
| byteIndex | int | Giriş tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | ArrayPtr\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |

### ReturnValue

Yazılan karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method


Bir tamponu kod çözümlerken elde edilen karakterleri al.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | ArrayPtr\<uint8_t\> | Çözülmesi gereken baytlar. |
| byteIndex | int | Giriş tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | ArrayPtr\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |

### ReturnValue

Yazılan karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) method


Bir tamponu kod çözümlerken elde edilen karakterleri al.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | const uint8_t * | Çözülmesi gereken baytlar. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | bool | Doğru ise, hesaplamadan sonra dahili çözücü durumunu temizler. |

### ReturnValue

Yazılan karakter sayısı.

## Ayrıca Bakınız

* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
