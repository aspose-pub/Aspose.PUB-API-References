---
title: "System::String::LastIndexOfAny method"
linktitle: "LastIndexOfAny"
second_title: "Aspose.PUB için C++"
description: "System::String::LastIndexOfAny method. Verilen karakterlerden herhangi birini tüm dize içinde geriye doğru arar. Son dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından bir önceki karakteri ve böyle devam eder. C++'ta bulunan ilk eşleşmenin indeksini döndürür."
type: docs
weight: 2400
url: /tr/cpp/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method


Geçilen karakterlerden herhangi birini tüm dizge içinde geriye doğru arar. Son dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin indeksini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |

### ReturnValue

Son eşleşen karakterin indeksi veya bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method


Geçilen karakterlerden herhangi birini alt dizge içinde geriye doğru arar. Son dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin indeksini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |
| startindex | int32_t | Aramaya başlanacak indeks. |

### ReturnValue

Son eşleşen karakterin indeksi veya bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method


Geçilen karakterlerden herhangi birini alt dizge içinde geriye doğru arar. Son dizge karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin indeksini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const ArrayPtr\<char_t\>\& | [Array](../../array/) aranacak karakterler. Sıra önemli değildir. |
| startindex | int32_t | Aramaya başlanacak indeks. |
| sayım | int32_t | İncelenecek karakter sayısı. |

### ReturnValue

Son eşleşen karakterin indeksi veya bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
