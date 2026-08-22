---
title: "System::Array::LastIndexOf metodu"
linktitle: "LastIndexOf"
second_title: "Aspose.PUB için C++"
description: "System::Array::LastIndexOf metodu. C++'da başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi öğeleri aralığında, belirtilen öğenin son görülüşünün indeksini belirler."
type: docs
weight: 5500
url: /tr/cpp/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında, belirtilen öğenin son oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranacak öğenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) içinde belirtilen öğeyi aramak için |
| değer | const ValueType\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | Aramanın başlatıldığı indeks |
| sayım | int | Aranacak aralıktaki öğe sayısı |

### ReturnValue

Öğe bulunursa belirtilen öğenin son görülüşünün indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Belirtilen dizide belirtilen öğenin son oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranacak öğenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) içinde belirtilen öğeyi aramak için |
| değer | const ValueType\& | Belirlenmesi gereken öğe indeksi |

### ReturnValue

Öğe bulunursa belirtilen öğenin son görülüşünün indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Belirtilen dizide, belirtilen indeks'ten başlayarak belirtilen öğenin son oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranacak öğenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| items | const ArrayPtr\<ArrayType\>\& | [Array](../) içinde belirtilen öğeyi aramak için |
| değer | const ValueType\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | Aramanın başlatıldığı indeks |

### ReturnValue

Öğe bulunursa belirtilen öğenin son görülüşünün indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
