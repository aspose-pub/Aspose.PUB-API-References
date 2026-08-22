---
title: "System::Collections::Generic::Dictionary::Dictionary yapıcısı"
linktitle: "Sözlük"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::Dictionary::Dictionary yapıcısı. C++'de boş sözlük oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructor


Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Ayrıca Bakınız

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(const map_t\&) constructor


Harita (map) üzerinden verileri kopyalar.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | const map_t\& | Verilerin kopyalanacağı harita. |

## Ayrıca Bakınız

* Typedef [map_t](../map_t/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor


Kopya yapıcı.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const SharedPtr\<IDictionary\<TKey, TValue\>\>\& | [Dictionary](../) verilerin kopyalanacağı. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Kopya yapıcı.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const SharedPtr\<IDictionary\<TKey, TValue\>\>\& | Kaynak sözlük. |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) kullanılacak nesne. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) kullanılacak. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(int) constructor


Önceden ayrılmış bir sözlük oluşturmayı karşılayan aşırı yükleme; aslında hiçbir tahsis yapmaz.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kapasite | int | Ayırılacak kapasite; yoksayılır. |

## Ayrıca Bakınız

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Boş bir sözlük oluşturur.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| capacity | int | [Dictionary](../) oluşturma sonrası kapasite; yoksayılır. |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) kullanılacak. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PUB for C++](../../../)
