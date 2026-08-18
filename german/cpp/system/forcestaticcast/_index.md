---
title: "System::ForceStaticCast Methode"
linktitle: "ForceStaticCast"
second_title: "Aspose.PUB für C++"
description: "System::ForceStaticCast Methode. Führt ein echtes static cast auf SmartPtr‑Objekten in C++ aus."
type: docs
weight: 19000
url: /de/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Führt ein echtes static cast auf [SmartPtr](../smartptr/) Objekten aus.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel‑Pointee‑Typ. |
| TFrom | Quell‑Pointee‑Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Quell‑Pointer. |

### ReturnValue

Gibt das Cast‑Ergebnis zurück, wenn das Casten erlaubt ist, andernfalls ist das Verhalten undefiniert.

## Siehe auch

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
