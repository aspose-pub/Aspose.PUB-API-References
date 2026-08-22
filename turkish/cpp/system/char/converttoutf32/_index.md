---
title: "System::Char::ConvertToUtf32 yöntemi"
linktitle: "ConvertToUtf32"
second_title: "Aspose.PUB için C++"
description: "System::Char::ConvertToUtf32 yöntemi. Belirtilen UTF-16 surrogate çiftini C++'da UTF-32 kod birimine dönüştürür."
type: docs
weight: 200
url: /tr/cpp/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) method


Belirtilen UTF-16 yedek çiftini UTF-32 kod birimine dönüştürür.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| highSurrogate | char_t | Dönüştürülecek UTF-16 surrogate çiftinin yüksek surrogate'ı |
| lowSurrogate | char_t | Dönüştürülecek UTF-16 surrogate çiftinin düşük surrogate'ı |

### ReturnValue

Dönüştürmeden elde edilen bir UTF-32 kod birimi

## Ayrıca Bakınız

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Char::ConvertToUtf32(const String\&, int) method


Bir dizede belirtilen konumdaki UTF-16 kodlu bir karakterin veya yedek çiftinin değerini UTF-32 kod birimine dönüştürür.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Bir karakter veya surrogate çifti içeren bir dize |
| indeks | int | Belirtilen dizedeki karakter veya surrogate çiftinin indeks konumu |

### ReturnValue

Dönüştürmeden elde edilen bir UTF-32 kod birimi

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
