---
title: "System::Nullable::NullableBoolHelper metodu"
linktitle: "NullableBoolHelper"
second_title: "Aspose.PUB için C++"
description: "System::Nullable::NullableBoolHelper metodu. Bu ve other'ın ikisinin de null olmamasını kontrol eden ve öyleyse bir lambda çağıran yardımcı işlev. C++'ta implementation.s içinde kullanılır."
type: docs
weight: 800
url: /tr/cpp/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper method


Bu ve **other**'ın ikisinin de null olmamasını kontrol eden ve böyleyse bir lambda çağıran yardımcı işlev. Uygulamalarda kullanılır.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


| Parametre | Açıklama |
| --- | --- |
| T1 | Diğer nullable türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | const T1\& | Karşılaştırma için diğer nullable değer. |
| f | const std::function\<bool()>\& | Her iki **this** ve **other** null değilse çağırılacak lambda. |
| default_if_both_are_null | bool | Her iki değer de null ise döndürülen değer. |

### ReturnValue

**this** veya **other** null ise false; her ikisi de null ise **default_if_both_are_null**; her ikisi de null değilse **f** çağrısının sonucu.

## Ayrıca Bakınız

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
