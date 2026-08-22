---
title: "System::operator- metodu"
linktitle: "operator-"
second_title: "Aspose.PUB için C++"
description: "System::operator- metodu. C++'ta belirtilen değerden belirtilen Decimal nesnesi tarafından temsil edilen değerin çıkarılması sonucunu temsil eden yeni bir Decimal sınıfı örneği döndürür."
type: docs
weight: 24700
url: /tr/cpp/system/operator-/
---
## System::operator-(const T\&, const Decimal\&) method


Belirtilen değerden belirtilen [Decimal](../decimal/) nesnesi tarafından temsil edilen değerin çıkarılması sonucunu temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği döndürür.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const T\& | Çıkarma yapılacak değer |
| d | const Decimal\& | Çıkarılan değeri temsil eden [Decimal](../decimal/) nesnesi |

### ReturnValue

**x**'ten **d** tarafından temsil edilen değerin çıkarılması sonucunda elde edilen bir değeri temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği.

## Ayrıca Bakınız

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator-(const T1\&, const Nullable\<T2\>\&) method


Null olmayan ve nullable (boş değer alabilen) değerleri çıkarır.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some - other.get_Value())> System::operator-(const T1 &some, const Nullable<T2> &other)
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

Alt istasyon sonucu.

## Ayrıca Bakınız

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator-(DayOfWeek, DayOfWeek) method


Haftanın iki günü arasındaki gün sayısını hesaplar.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | DayOfWeek | Azalan |
| b | DayOfWeek | Çıkarılan |

### ReturnValue

Hafta içi günleri **a** ve **b** arasındaki gün sayısı; dönüş değeri, *goes* sonrası negatif bir sayı ise ****

## Ayrıca Bakınız

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Sağ el delegesinde bulunan tüm geri çağrıları, sol el delegesinin geri çağrı listesinin sonundan ayırır.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Geri çağrıların kaldırılacağı delegesi. |
| rhv | MulticastDelegate\<T\> | Geri çağrıları kaldırılacak delegesi. |

### ReturnValue

Sol el değerinin geri çağrılarını içeren, ancak sağ el değerinin geri çağrılarını içermeyen bir delegeyi döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
