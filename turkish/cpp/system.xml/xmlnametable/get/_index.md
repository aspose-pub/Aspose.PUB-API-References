---
title: "System::Xml::XmlNameTable::Get metodu"
linktitle: "Get"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNameTable::Get metodu. Türetilmiş bir sınıfta geçersiz kılındığında, verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomize edilmiş dizeyi C++'da alır."
type: docs
weight: 200
url: /tr/cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Türetilmiş bir sınıfta geçersiz kılındığında, verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomize edilmiş dizeyi alır.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | const ArrayPtr\<char16_t\>\& | Aranacak ismi içeren karakter dizisi. |
| ofset | int32_t | İsmin ilk karakterini belirten dizi içindeki sıfır tabanlı indeks. |
| uzunluk | int32_t | İsmin karakter sayısı. |

### ReturnValue

Dize zaten atomize edilmemişse atomize edilmiş dize ya da **nullptr**. **length** sıfır ise, [String::Empty](../../../system/string/empty/) döndürülür.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlNameTable::Get(const String\&) method


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyle aynı değeri içeren atomize edilmiş dizeyi alır.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | const String\& | Aranacak isim. |

### ReturnValue

Dize zaten atomize edilmemişse atomize edilmiş dize ya da **nullptr**.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
