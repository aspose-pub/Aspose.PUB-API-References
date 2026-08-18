---
title: "Methode System::ConstCast"
linktitle: "ConstCast"
second_title: "Aspose.PUB für C++"
description: "Methode System::ConstCast. Ende veralteter Casts in C++."
type: docs
weight: 15000
url: /de/cpp/system/constcast/
---
## System::ConstCast method


Ende veralteter Casts.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel‑Pointee‑Typ. |
| TFrom | Quell‑Pointee‑Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Quell‑Pointer. |

### ReturnValue

Cast‑Ergebnis, falls der Cast erlaubt ist, sonst nullptr.
## Hinweise


Führt const cast auf [SmartPtr](../smartptr/) Objekten aus.
## Siehe auch

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
