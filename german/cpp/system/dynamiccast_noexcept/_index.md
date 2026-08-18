---
title: "System::DynamicCast_noexcept method"
linktitle: "DynamicCast_noexcept"
second_title: "Aspose.PUB für C++"
description: "System::DynamicCast_noexcept method. Alte veraltete Casts. Wird in zukünftigen Versionen in C++ entfernt werden."
type: docs
weight: 16500
url: /de/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Alte veraltete Casts. Werden in zukünftigen Versionen entfernt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel‑Exception‑Typ. |
| TFrom | Quell‑Exception‑Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const TFrom\& | Quell‑Pointer. |

### ReturnValue

Cast‑Ergebnis, falls der Cast erlaubt ist, sonst nullptr.
## Hinweise


Führt einen dynamischen Cast auf Exception‑Objekten durch. ## Deprecated
Zurückgelassen für Abwärtskompatibilität. Verwenden Sie stattdessen AsCast.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Führt einen dynamischen Cast auf [SmartPtr](../smartptr/)-Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel‑Pointee‑Typ. |
| TFrom | Quell‑Pointee‑Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Quell‑Pointer. |

### ReturnValue

Cast‑Ergebnis, falls der Cast erlaubt ist, sonst nullptr.

## Deprecated
Zurückgelassen für Abwärtskompatibilität. Verwenden Sie stattdessen AsCast.

## Siehe auch

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Führt einen dynamischen Cast von Objekten zu Exception‑Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel‑Exception‑Typ. |
| TFrom | [Objekt](../object/) Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Quell‑Pointer. |

### ReturnValue

Cast‑Ergebnis, falls der Cast erlaubt ist, sonst nullptr.

## Deprecated
Zurückgelassen für Abwärtskompatibilität. Verwenden Sie stattdessen AsCast.

## Siehe auch

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
