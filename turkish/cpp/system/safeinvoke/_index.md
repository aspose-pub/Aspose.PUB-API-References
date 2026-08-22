---
title: "System::SafeInvoke method"
linktitle: "SafeInvoke"
second_title: "Aspose.PUB için C++"
description: "System::SafeInvoke method. C++'da ''?.'' operatörünün çevirisinin uygulanması."
type: docs
weight: 33500
url: /tr/cpp/system/safeinvoke/
---
## System::SafeInvoke method


'?.' operatörünün çevirisinin uygulanması.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 expr, T1 func)
```


| Parametre | Açıklama |
| --- | --- |
| T0 | ifade türü. |
| T1 | ‘WhenTrue’ ifadesini kapsayan lambda türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | T0 | ifade değeri. |
| func | T1 | ‘WhenTrue’ ifadesi fonktöre bağlandı. |

### ReturnValue

Eğer expr değeri null değilse, değeri ilk argüman olarak çağrılan func'ı döndürür, aksi takdirde null döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
