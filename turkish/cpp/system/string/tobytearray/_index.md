---
title: "System::String::ToByteArray metodu"
linktitle: "ToByteArray"
second_title: "Aspose.PUB için C++"
description: "System::String::ToByteArray metodu. Dizeyi veya alt dizeyi C++'ta bayt dizisine dönüştürür."
type: docs
weight: 4500
url: /tr/cpp/system/string/tobytearray/
---
## String::ToByteArray method


Dizgeyi veya alt dizgeyi bayt dizisine dönüştürür.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=true) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int32_t | Alt dize başlangıç indeksi. |
| uzunluk | int32_t | Alt dize uzunluğu. |
| LE | bool | Doğru ise, karakterleri küçük endian kullanarak kodlayın; aksi takdirde büyük endian kullanın. |

### ReturnValue

[Array](../../array/) containing bytes representing characters of the string.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
