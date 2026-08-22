---
title: "System::Array::IndexOf yöntemi"
linktitle: "IndexOf"
second_title: "Aspose.PUB için C++"
description: "System::Array::IndexOf yöntemi. Belirtilen öğenin dizideki ilk oluşumunun indeksini C++'da belirler."
type: docs
weight: 2900
url: /tr/cpp/system/array/indexof/
---
## Array::IndexOf(const T\&) const method


Dizide belirtilen öğenin ilk oluşumunun indeksini belirler.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öğe | const T\& | Belirlenmesi gereken öğe indeksi |

### ReturnValue

Öğe bulunursa belirtilen öğenin dizideki ilk oluşumunun indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Dizide belirtilen öğenin ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranacak öğenin türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<ArrayType\>\& | [Array](../) içinde belirtilen öğeyi aramak için |
| değer | const ValueType\& | Belirlenmesi gereken öğe indeksi |

### ReturnValue

Öğe bulunursa belirtilen öğenin ilk oluşumunun indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Belirtilen dizide, belirtilen indeks'ten başlayarak belirtilen öğenin ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
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

### ReturnValue

Öğe bulunursa belirtilen öğenin dizideki ilk oluşumunun indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Başlangıç indeksi ve aralıktaki öğe sayısı ile belirtilen dizi aralığında, belirtilen öğenin ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
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

Öğe bulunursa belirtilen öğenin dizideki ilk oluşumunun indeksi, aksi takdirde -1

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
