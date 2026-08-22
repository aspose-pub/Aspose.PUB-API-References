---
title: "System::operator!= yöntemi"
linktitle: "operator!="
second_title: "Aspose.PUB için C++"
description: "C++'da sınıfın operator!= yöntemini nasıl kullanılır."
type: docs
weight: 22400
url: /tr/cpp/system/operator!=/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## Ayrıca Bakınız

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


| Parametre | Açıklama |
| --- | --- |
| Chars | [String](../string/) literal tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | Chars\& | Karşılaştırma için [String](../string/) literal. |
| right | const String\& | Karşılaştırma için [String](../string/). |

### ReturnValue

Dizeler eşleşirse false, aksi takdirde true.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | String'e dönüştürmek ve karşılaştırmak için [Object](../object/). |
| right | const String\& | Karşılaştırma için [String](../string/). |

### ReturnValue

Nesnenin string temsili string'e eşitse false, aksi takdirde true.

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Geçerli ve belirtilen nesneler tarafından temsil edilen URI'ların eşit olmamasını belirler.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | Karşılaştırılacak ilk [Uri](../uri/) nesnesi |
| uri2 | const SharedPtr\<Uri\>\& | Karşılaştırılacak ikinci [Uri](../uri/) nesnesi |

### ReturnValue

URI'lar eşit değilse true, aksi takdirde - false

## Ayrıca Bakınız

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Eşit olmayan karşılaştırma iki akıllı işaretçiyi karşılaştırır.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


| Parametre | Açıklama |
| --- | --- |
| X | İlk işaretçinin işaret ettiği tip. |
| Y | İkinci işaretçinin işaret ettiği tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Karşılaştırılacak ilk işaretçi. |
| y | const SmartPtr\<Y\>\& | Karşılaştırılacak ikinci gösterici. |

### ReturnValue

Göstericiler eşleşirse false, aksi takdirde true.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const SmartPtr\<X\>\&, const Y *) method


Akıllı göstericinin basit (C) göstericiye karşı eşitsizlik karşılaştırması.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


| Parametre | Açıklama |
| --- | --- |
| X | Akıllı göstericinin türü. |
| Y | Basit göstericinin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | Karşılaştırılacak akıllı gösterici (sol). |
| y | const Y * | Karşılaştırılacak gösterici (sağ). |

### ReturnValue

Göstericiler eşleşirse false, aksi takdirde true.

## Ayrıca Bakınız

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const T1\&, const Nullable\<T2\>\&) method


Belirtilen değerin, belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değere eşit olmamasını, bu değerlere [operator!=()](./) uygulanarak belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | İlk karşılaştırılan değerin türü |
| T2 | İkinci karşılaştırılan değeri temsil eden [Nullable](../nullable/) nesnesinin temel türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bazı | const T1\& | İlk karşılaştırılan olarak kullanılacak değere sabit bir referans |
| other | const Nullable\<T2\>\& | İkinci karşılaştırılan olarak kullanılacak temsil edilen değere sahip [Nullable](../nullable/) nesnesine sabit bir referans |

### ReturnValue

Karşılaştırılanlar eşit değilse true, aksi takdirde - false

## Ayrıca Bakınız

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(const X *, const SmartPtr\<Y\>\&) method


Akıllı göstericinin basit (C) göstericiye karşı eşitlik karşılaştırması.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


| Parametre | Açıklama |
| --- | --- |
| X | Basit göstericinin türü. |
| Y | Akıllı göstericinin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const X * | Karşılaştırılacak gösterici (sağ). |
| y | const SmartPtr\<Y\>\& | Karşılaştırılacak akıllı gösterici (sol). |

### ReturnValue

Göstericiler eşleşirse false, aksi takdirde true.

## Ayrıca Bakınız

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) method


Akıllı göstericinin null olmadığını kontrol eder.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


| Parametre | Açıklama |
| --- | --- |
| X | Göstericinin işaret ettiği nesnenin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | SmartPtr\<X\> const\& | Kontrol edilecek gösterici. |

### ReturnValue

Gösterici null ise false, aksi takdirde true.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## Ayrıca Bakınız

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) method


Belirtilen [Nullable](../nullable/) nesnesinin null olmayan bir değeri temsil edip etmediğini belirler.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | std::nullptr_t | Test etmek için bir [Nullable](../nullable/) nesnesine sabit referans |

### ReturnValue

Belirtilen nesne null olmayan bir değeri temsil ediyorsa doğru, aksi takdirde yanlış

## Ayrıca Bakınız

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, const String\&) method


Dizenin null olup olmadığını kontrol eder.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | std::nullptr_t | Kontrol için [String](../string/) |

### ReturnValue

Dize null ise yanlış, aksi takdirde doğru.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, DateTime) method




```cpp
bool System::operator!=(std::nullptr_t, DateTime)
```

## Ayrıca Bakınız

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) method


Akıllı göstericinin null olmadığını kontrol eder.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


| Parametre | Açıklama |
| --- | --- |
| X | Göstericinin işaret ettiği nesnenin türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | std::nullptr_t | Kontrol edilecek gösterici. |

### ReturnValue

Gösterici null ise false, aksi takdirde true.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator!=(std::nullptr_t, TimeSpan)
```

## Ayrıca Bakınız

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator!=(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) işaretçi türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | Karşılaştırma için [String](../string/) işaretçi. |
| right | const String\& | Karşılaştırma için [String](../string/). |

### ReturnValue

Dizeler eşleşirse false, aksi takdirde true.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
