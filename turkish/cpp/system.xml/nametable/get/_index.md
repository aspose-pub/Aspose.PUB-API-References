---
title: "System::Xml::NameTable::Get method"
linktitle: "Get"
second_title: "Aspose.PUB için C++"
description: "System::Xml::NameTable::Get yöntemi. Verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomize edilmiş dizeyi C++'de döndürür."
type: docs
weight: 300
url: /tr/cpp/system.xml/nametable/get/
---
## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomlaştırılmış dizeyi döndürür.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | const ArrayPtr\<char16_t\>\& | Bulunacak adı içeren karakter dizisi. |
| başlangıç | int32_t | İsmin ilk karakterini belirten dizi içindeki sıfır tabanlı indeks. |
| len | int32_t | İsmin karakter sayısı. |

### ReturnValue

Atomize edilmiş dize ya da dize henüz atomize edilmemişse **nullptr**. **len** sıfır ise, [String::Empty](../../../system/string/empty/) döndürülür.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## NameTable::Get(const String\&) method


Belirtilen değere sahip atomlaştırılmış dizeyi döndürür.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const String\& | Bulunacak ad. |

### ReturnValue

Atomize edilmiş dize nesnesi ya da dize henüz atomize edilmemişse **nullptr**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
