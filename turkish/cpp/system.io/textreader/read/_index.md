---
title: "System::IO::TextReader::Read metodu"
linktitle: "Oku"
second_title: "Aspose.PUB için C++"
description: "System::IO::TextReader::Read metodu. C++'ta akıştan tek bir karakter okur."
type: docs
weight: 400
url: /tr/cpp/system.io/textreader/read/
---
## TextReader::Read() method


Akıştan tek bir karakter okur.

```cpp
virtual int System::IO::TextReader::Read()
```


### ReturnValue

UTF-16 kodlamasıyla kodlanmış karakter okunur; eğer okunan karakter UTF-16 kodlamasında iki kod noktasına karşılık geliyorsa yalnızca yüksek surragate döndürülür.

## Ayrıca Bakınız

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## TextReader::Read(ArrayPtr\<char_t\>, int, int) method


Akıştan belirtilen sayıda karakteri okur ve belirtilen konumdan başlayarak belirtilen karakter dizisine yazar.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon | ArrayPtr\<char_t\> | Akıştan okunan karakterleri yazmak için UTF-16 karakter dizisi |
| indeks | int | **buffer** içinde yazmaya başlanacak 0 tabanlı bir indeks |
| sayım | int | Akıştan okunacak karakter sayısı |

### ReturnValue

Akıştan okunan karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
