---
title: "System::Collections::Generic::operator== Methode"
linktitle: "operator=="
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::operator== Methode. Vergleicht zwei Schlüssel‑Wert‑Paare nach ''equals''‑Semantik. Verwendet den Operator == oder die EqualsTo‑Methode für sowohl Schlüssel als auch Werte, je nachdem, was in C++ definiert ist."
type: docs
weight: 5600
url: /de/cpp/system.collections.generic/operator==/
---
## System::Collections::Generic::operator== method


Vergleicht zwei Schlüssel‑Wert‑Paare nach 'equals'‑Semantik. Verwendet den Operator == oder die EqualsTo‑Methode für sowohl Schlüssel als auch Werte, je nachdem, was definiert ist.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links | const KeyValuePair\<TKey, TValue\>\& | Linker Operand. |
| rechts | const KeyValuePair\<TKey, TValue\>\& | Rechter Operand. |

### ReturnValue

Wahr, wenn sowohl Schlüssel als auch Werte übereinstimmen, sonst falsch.

## Siehe auch

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
