---
title: "System::IO::File::OpenText metodu"
linktitle: "OpenText"
second_title: "Aspose.PUB için C++"
description: "System::IO::File::OpenText metodu. Belirtilen mevcut dosyayı, UTF-8 kodlamasını kullanarak, paylaşım olmadan C++'ta metin okuma için açar."
type: docs
weight: 2100
url: /tr/cpp/system.io/file/opentext/
---
## File::OpenText method


Belirtilen mevcut dosyayı UTF-8 kodlamasını kullanarak metin okumak için, paylaşım olmadan açar.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Açılacak dosyanın yolu |
| encoding | const EncodingPtr\& | Kullanılacak karakter kodlaması |

### ReturnValue

Açılan dosyayla ilişkili bir [StreamWriter](../../streamwriter/) nesnesine ait paylaşımlı gösterici

## Ayrıca Bakınız

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
