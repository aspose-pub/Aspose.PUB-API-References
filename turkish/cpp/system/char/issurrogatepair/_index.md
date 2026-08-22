---
title: "System::Char::IsSurrogatePair yöntemi"
linktitle: "IsSurrogatePair"
second_title: "Aspose.PUB için C++"
description: "System::Char::IsSurrogatePair yöntemi. C++'ta bir UTF-16 surrogate çifti için iki belirtilen karakterin olup olmadığını belirler."
type: docs
weight: 1700
url: /tr/cpp/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method


Belirtilen iki karakterin UTF-16 surrogate çifti olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| highSurrogate | char_t | Yüksek surrogate olup olmadığı test edilen bir karakter |
| lowSurrogate | char_t | Düşük surrogate olup olmadığı test edilen bir karakter |

### ReturnValue

Belirtilen karakterler bir surrogate çifti oluşturuyorsa doğru, aksi takdirde - yanlış

## Ayrıca Bakınız

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Char::IsSurrogatePair(const String\&, int) method


Belirtilen karakter tamponundaki ardışık iki karakterin surrogate çift olup olmadığını belirler.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const String\& | Bir dize |
| indeks | int | Test edilecek karakter dizisinin başladığı belirtilen tampondaki sıfır tabanlı indeks |

### ReturnValue

Belirtilen karakterler bir surrogate çifti ise true, aksi takdirinde - false

## Ayrıca Bakınız

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
