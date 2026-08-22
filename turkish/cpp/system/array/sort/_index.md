---
title: "System::Array::Sort yöntemi"
linktitle: "Sırala"
second_title: "Aspose.PUB için C++"
description: "System::Array::Sort yöntemi. C++'ta operator< kullanılarak karşılaştırılan anahtar değerlerine göre, birincisi anahtarları ve ikincisi karşılık gelen öğeleri içeren iki diziyi sıralar."
type: docs
weight: 5800
url: /tr/cpp/system/array/sort/
---
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Anahtarları içeren bir dizi ve diğer dizi - karşılık gelen öğeler - anahtarları içeren dizinin değerlerine göre, öğeleri operator< kullanılarak karşılaştırarak iki diziyi sıralar.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


| Parametre | Açıklama |
| --- | --- |
| TKey | **keys** dizisindeki öğelerin tipi |
| TValue | **items** dizisindeki öğelerin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) anahtar değerlerini içeren |
| items | const ArrayPtr\<TValue\>\& | [Array](../) **keys** dizisindeki anahtar değerlerine eşlenen öğeleri içeren |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Anahtarları içeren bir dizi ve diğer dizi - karşılık gelen öğeler - anahtarları içeren dizinin değerlerine göre, öğeleri varsayılan karşılaştırıcıyı kullanarak karşılaştırarak iki diziyi sıralar.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


| Parametre | Açıklama |
| --- | --- |
| TKey | **keys** dizisindeki öğelerin tipi |
| TValue | **items** dizisindeki öğelerin tipi |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) anahtar değerlerini içeren |
| items | const ArrayPtr\<TValue\>\& | [Array](../) **keys** dizisindeki anahtar değerlerine eşlenen öğeleri içeren |
| indeks | int | Sıralanacak aralığın başlangıcını belirten indeks |
| uzunluk | int | Sıralanacak aralıktaki eleman sayısı |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&) method


Belirtilen dizideki öğeleri varsayılan karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Hedef dizi |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Belirtilen dizideki öğeleri belirtilen karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Hedef dizi |
| karşılaştırıcı | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Dizinin elemanlarını karşılaştırmak için kullanılan IComparer<T> nesnesi |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


UYGULANMADI.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Belirtilen dizideki bir öğe aralığını varsayılan karşılaştırıcıyı kullanarak sıralar.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Hedef dizi |
| startIndex | int | Sıralanacak eleman aralığının başlangıcını belirten indeks |
| sayım | int | Sıralanacak eleman aralığının boyutu |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
