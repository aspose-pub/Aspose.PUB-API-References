---
title: "System::String::IndexOfAny method"
linktitle: "IndexOfAny"
second_title: "Aspose.PUB için C++"
description: "System::String::IndexOfAny yöntemi. C++'da karakter ileri arama."
type: docs
weight: 1500
url: /tr/cpp/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method


Karakter ileri arama.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Aranacak karakter. |
| startIndex | int | Aramaya başlanacak indeks. |

### ReturnValue

startIndex'ten itibaren ilk karakter konumunun indeksi, bulunamazsa -1.

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method


Geçilen karakterlerden herhangi birini tüm dizge boyunca arar. İlk dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinci karakteri ve böyle devam eder. Hedef karakterlerden herhangi biriyle eşleşen ilk karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |

### ReturnValue

ilk eşleşen karakterin indeksi, bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Geçilen karakterlerden herhangi birini alt dizge içinde arar. İlk dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinci karakteri ve böyle devam eder. Hedef karakterlerden herhangi biriyle eşleşen ilk karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |
| startindex | int32_t | Aramaya başlanacak indeks. |

### ReturnValue

ilk eşleşen karakterin indeksi, bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Geçilen karakterlerden herhangi birini alt dizge içinde arar. İlk dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinci karakteri ve böyle devam eder. Hedef karakterlerden herhangi biriyle eşleşen ilk karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |
| startindex | int32_t | Aramaya başlanacak indeks. |
| sayım | int32_t | İncelenecek karakter sayısı. |

### ReturnValue

ilk eşleşen karakterin indeksi, bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::IndexOfAny(const String\&, int) const method


Dolayısıyla bu içinde str'nin tüm karakterlerini arar. İlk karakter bulunursa konumu döndürülür, aksi takdirde ikinci karakter ve böyle devam eder.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const String\& | [String](../) aranan karakterler. Karakterlerin sırası önemlidir. |
| startIndex | int | arama başlangıç konumu. |

### ReturnValue

ilk bulunan karakterin indeksi, hiç bulunamazsa -1.

## Ayrıca Bakınız

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
