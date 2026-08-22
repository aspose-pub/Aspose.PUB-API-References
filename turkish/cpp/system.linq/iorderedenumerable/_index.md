---
title: "System::Linq::IOrderedEnumerable sınıfı"
linktitle: "IOrderedEnumerable"
second_title: "Aspose.PUB için C++"
description: "System::Linq::IOrderedEnumerable sınıfı. C++'da sıralı bir dizi temsil eder."
type: docs
weight: 300
url: /tr/cpp/system.linq/iorderedenumerable/
---
## IOrderedEnumerable class


Sıralı bir diziyi temsil eder.

```cpp
template<typename T>class IOrderedEnumerable : public System::Collections::Generic::IEnumerable<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Dizinin öğelerinin türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [GetEnumerator](./getenumerator/)() override | Yineleyiciyi alır. |
| [IOrderedEnumerable](./iorderedenumerable/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&, const Comparator\&) |  |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<T, Key\>\&) | Bir anahtara göre dizideki öğeleri artan sırada sonraki bir sıralama gerçekleştirir. |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<Source, Key\>\&) |  |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Comparator](./comparator/) | RTTI bilgisi. |

## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Linq](../)
* Library [Aspose.PUB for C++](../../)
