---
title: "System::Text::ICUEncoder::GetBytes yöntemi"
linktitle: "GetBytes"
second_title: "Aspose.PUB için C++"
description: "System::Text::ICUEncoder::GetBytes yöntemi. Bir tamponun kodlanmasından elde edilen baytları C++'ta alır."
type: docs
weight: 500
url: /tr/cpp/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Bir tamponu kodlarken elde edilen baytları al.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Kodlanacak karakterler. |
| charIndex | int | Kaynak dizi ofseti. |
| charCount | int | Kaynak alt dizi uzunluğu. |
| baytlar | ArrayPtr\<uint8_t\> | Hedef bayt tamponu. |
| byteIndex | int | Hedef tampon ofseti. |
| flush | bool | Doğruysa, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### ReturnValue

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Bir tamponu kodlarken elde edilen baytları al.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| charCount | int | Kaynak dizi uzunluğu. |
| baytlar | uint8_t * | Hedef bayt tamponu. |
| byteCount | int | Hedef tampon boyutu. |
| flush | bool | Doğruysa, hesaplamadan sonra dahili kodlayıcı durumunu temizler. |

### ReturnValue

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
