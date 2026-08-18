---
title: "System::AsCast Methode"
linktitle: "AsCast"
second_title: "Aspose.PUB für C++"
description: "System::AsCast Methode. Castet den Quelltyp zum Ergebnis­typ mittels ''as''‑Operator‑Cast. Wird verwendet, wenn ein einfacher, konstruktorähnlicher Cast in C++ benötigt wird."
type: docs
weight: 12900
url: /de/cpp/system/ascast/
---
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird verwendet, wenn ein einfacher, konstruktorähnlicher Cast benötigt wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird verwendet, wenn Quell- und Ergebnis­typ identisch sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird für Ausnahme‑Wrapper verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird zum Casten eines Objekts in eine Ausnahme verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird verwendet, wenn sowohl Quell‑ als auch Ergebnis‑Smart‑Pointer sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird verwendet, wenn sowohl Quell‑ als auch Ergebnis‑Smart‑Pointer sind (mit explizitem SmartPtr<...> im Ergebnis­typ).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird zum Unboxing eines Objekts in ein Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt ein leeres Nullable zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Ungültiges Unboxing zu einem Nicht‑Objekt‑Typ.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Gibt immer null zurück.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird zum Boxing eines Nullable‑Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Castet den Quelltyp zum Ergebnis­typ mittels 'as'‑Operator‑Cast. Wird zum Boxing eines allgemeinen Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mit dem 'as'-Operator‑Cast um. Wird für das Ent‑boxing von Zeichenketten verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mit dem 'as'-Operator‑Cast um. Wird für das Casting von nullptr verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Wandelt den Quelltyp in den Ergebnis­typ mit dem 'as'-Operator‑Cast um. Wird zum Casten zwischen Arrays verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parameter | Beschreibung |
| --- | --- |
| Quelle | Der Quelltyp. |
| Ergebnis | Der Ergebnis­typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### ReturnValue

Das Cast‑Ergebnis. Gibt nullptr zurück, wenn für kein Array‑Element eine Konvertierung verfügbar ist.

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
