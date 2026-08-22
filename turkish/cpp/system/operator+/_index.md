---
title: "System::operator+ method"
linktitle: "operator+"
second_title: "Aspose.PUB için C++"
description: "System::operator+ method. C++'de dize birleştirme."
type: docs
weight: 24100
url: /tr/cpp/system/operator+/
---
## System::operator+(const char_t, const String\&) method


[String](../string/) concatenation.

```cpp
String System::operator+(const char_t left, const String &right)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | const char_t | Dizeye eklemek için karakter. |
| right | const String\& | [String](../string/) birleştirilecek. |

### ReturnValue

Birleştirilmiş dize.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator+(const T\&, const Decimal\&) method


Belirtilen değerin ve belirtilen [Decimal](../decimal/) nesnesi tarafından temsil edilen değerin toplamını temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği döndürür.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const T\& | İlk toplama öğesi |
| d | const Decimal\& | İkinci toplama öğesini temsil eden [Decimal](../decimal/) nesnesine sabit referans. |

### ReturnValue

**x** ve **d** tarafından temsil edilen değerin toplamını temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği.

## Ayrıca Bakınız

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator+(const T1\&, const Nullable\<T2\>\&) method


Null olmayan ve null olabilen değerleri toplar.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some+other.get_Value())> System::operator+(const T1 &some, const Nullable<T2> &other)
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Sol operand türü. |
| T2 | Sağ operand türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bazı | const T1\& | Sol operand. |
| diğer | const Nullable\<T2\>\& | Sağ operand. |

### ReturnValue

Toplama sonucu.

## Ayrıca Bakınız

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Sağ el delegesindeki tüm geri aramaları, sol el delegesinin geri arama listesine sonuna bağlar.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Geri aramaların eklendiği delege. |
| rhv | MulticastDelegate\<T\> | Geri aramaları eklenen delege. |

### ReturnValue

Sol el değerinin geri aramalarını ve ardından sağ el değerinin geri aramalarını içeren bir delege döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) literal tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | T\& | Dizeye eklemek için bir literal. |
| right | const String\& | [String](../string/) birleştirilecek. |

### ReturnValue

Birleştirilmiş dize.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) işaretçi türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | [String](../string/) dizeye eklemek için işaretçi. |
| right | const String\& | [String](../string/) birleştirilecek. |

### ReturnValue

Birleştirilmiş dize.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
