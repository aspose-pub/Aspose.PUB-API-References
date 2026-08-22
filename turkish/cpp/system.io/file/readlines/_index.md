---
title: "System::IO::File::ReadLines yöntemi"
linktitle: "ReadLines"
second_title: "Aspose.PUB için C++"
description: "System::IO::File::ReadLines yöntemi. Belirtilen metin dosyasının içeriğini belirtilen karakter kodlamasını kullanarak satır satır okur ve C++'ta dosyanın içeriğinin tek bir satırını temsil eden dize koleksiyonunu döndürür."
type: docs
weight: 2600
url: /tr/cpp/system.io/file/readlines/
---
## File::ReadLines method


Belirtilen metin dosyasının içeriğini satır satır, belirtilen karakter kodlamasını kullanarak okur ve dosyanın içeriğinin tek bir satırını temsil eden dize koleksiyonunu döndürür.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Okunacak dosyanın yolu |
| encoding | const EncodingPtr\& | Kullanılacak karakter kodlaması |

### ReturnValue

Belirtilen dosyanın içeriğini temsil eden yinelenebilir dize koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
