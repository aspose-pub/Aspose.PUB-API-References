---
title: "System::ExplicitCast Methode"
linktitle: "ExplicitCast"
second_title: "Aspose.PUB für C++"
description: "System::ExplicitCast Methode. Castet den Quelltyp in den Ergebnis-Typ mittels explizitem Cast. Wird verwendet, wenn Quell- und Ergebnis-Typ in C++ identisch sind."
type: docs
weight: 17400
url: /de/cpp/system/explicitcast/
---
## System::ExplicitCast(const Source\&) method


Castet den Quelltyp in den Ergebnis-Typ mittels explizitem Cast. Wird verwendet, wenn Quell- und Ergebnis-Typ identisch sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Castet den Quelltyp in den Ergebnis-Typ mittels explizitem Cast. Wird verwendet, wenn ein einfacher, konstruktorähnlicher Cast benötigt wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Castet den Quelltyp in den Ergebnis-Typ mittels explizitem Cast. Wird für Ausnahme-Wrapper verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Casten von Objekt zu Ausnahme verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird verwendet, wenn Quelle und Ergebnis beide Smart‑Pointer sind (ohne expliziten SmartPtr<...> im Ergebnis­typ).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird verwendet, wenn Quelle und Ergebnis beide Smart‑Pointer sind (mit explizitem SmartPtr<...> im Ergebnis­typ).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Unboxing eines Objekts in einen Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Boxen eines Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Unboxing eines Nullable‑Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Boxen von Enums verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird für allgemeines Boxing verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird für das Boxing von [System::String](../string/) verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird für allgemeines Unboxing verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird für das Casten von nullptr verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird zum Casten zwischen Arrays verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(Source) method


Wandelt den Quelltyp in den Ergebnis­typ mittels explizitem Cast um. Wird verwendet, wenn ein roher Zeiger in einen Smart‑Pointer gecastet wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | Source | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
