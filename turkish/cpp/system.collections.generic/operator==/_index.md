---
title: "System::Collections::Generic::operator== metodu"
linktitle: "operator=="
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::operator== metodu. ''equals'' semantiğini kullanarak iki anahtar-değer çiftini karşılaştırır. Her iki anahtar ve değer için operator == ya da EqualsTo metodunu kullanır; hangisi C++'ta tanımlıysa."
type: docs
weight: 5600
url: /tr/cpp/system.collections.generic/operator==/
---
## System::Collections::Generic::operator== method


İki anahtar-değer çiftini 'equals' semantiğini kullanarak karşılaştırır. Her iki anahtar ve değer için operator == ya da EqualsTo metodunu kullanır; hangisi tanımlıysa.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtar türü. |
| TValue | Değer türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | const KeyValuePair\<TKey, TValue\>\& | Sol taraf operandı. |
| sağ | const KeyValuePair\<TKey, TValue\>\& | Sağ taraf operandı. |

### ReturnValue

Her iki anahtar ve değer eşleşiyorsa doğru, aksi takdirde yanlıştır.

## Ayrıca Bakınız

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
