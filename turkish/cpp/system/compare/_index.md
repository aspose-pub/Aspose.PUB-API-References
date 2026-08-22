---
title: "System::Compare yöntemi"
linktitle: "Compare"
second_title: "Aspose.PUB için C++"
description: "System::Compare yöntemi. C++'ta iki değeri karşılaştırır."
type: docs
weight: 14700
url: /tr/cpp/system/compare/
---
## System::Compare(const TA\&, const TB\&) method


İki değeri karşılaştırır.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parametre | Açıklama |
| --- | --- |
| TA | İlk karşılaştırılanın tipi |
| TB | İkinci karşılaştıranın türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const TA\& | İlk karşılaştırılan değer |
| b | const TB\& | İkinci karşılaştırılan değer |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::Compare(const TA\&, const TB\&) method


İki kayan nokta değerini karşılaştırır.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


| Parametre | Açıklama |
| --- | --- |
| TA | İlk karşılaştırılanın tipi |
| TB | İkinci karşılaştıranın türü |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const TA\& | İlk karşılaştırılan değer |
| b | const TB\& | İkinci karşılaştırılan değer |

### ReturnValue

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
