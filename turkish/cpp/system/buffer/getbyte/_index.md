---
title: "System::Buffer::GetByte yöntemi"
linktitle: "GetByte"
second_title: "Aspose.PUB için C++"
description: "System::Buffer::GetByte yöntemi. Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve C++'ta belirtilen bayt offsetindeki bayt değerini alır."
type: docs
weight: 300
url: /tr/cpp/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) method


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt ofsetindeki bayt değerini alır.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


| Parametre | Açıklama |
| --- | --- |
| T | Dizinin eleman tipleri |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | const SharedPtr\<Array\<T\>\>\& | Hedef dizi |
| indeks | int | Alınacak baytin sıfır tabanlı offseti |

### ReturnValue

Belirtilen indeksteki bayt değeri

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) method


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt ofsetindeki bayt değerini alır.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


| Parametre | Açıklama |
| --- | --- |
| T | Dizi görünümünün eleman türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | const System::Details::ArrayView\<T\>\& | Hedef dizi görünümü |
| indeks | int | Alınacak baytin sıfır tabanlı offseti |

### ReturnValue

Belirtilen indeksteki bayt değeri

## Ayrıca Bakınız

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) method


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt ofsetindeki bayt değerini alır.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


| Parametre | Açıklama |
| --- | --- |
| T | Yığın dizisinin eleman türü |
| N | Yığın dizisinin boyutu |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | const System::Details::StackArray\<T, N\>\& | Hedef yığın dizisi |
| indeks | int | Alınacak baytin sıfır tabanlı offseti |

### ReturnValue

Belirtilen indeksteki bayt değeri

## Ayrıca Bakınız

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
