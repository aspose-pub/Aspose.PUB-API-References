---
title: "Methode System::ObjectExt::Is"
linktitle: "Is"
second_title: "Aspose.PUB für C++"
description: "Methode System::ObjectExt::Is. Implementiert die Übersetzung des ''is''-Operators. Spezialisierung für String-Literal in C++."
type: docs
weight: 1000
url: /de/cpp/system/objectext/is/
---
## ObjectExt::Is(const char16_t *) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für String-Literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) Literal. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Ausnahmewrapper-Typen.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const ExceptionWrapper\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Nullable\<U\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für den Typ [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Nullable\<U\>\& | [Nullable](../../nullable/) Typ. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Werttypen.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für nicht konvertierbare Typen.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Gibt immer false zurück, da die Typen nicht konvertierbar sind.

## Siehe auch

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Nullable-Typen.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare Typen mit definiertem ==-Operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für boxbare Typen ohne definierten ==-Operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Aufzählungstypen.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Typ des referenzierten Objekts. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen, optimiert für 'final'-Klassen.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Getesteter Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const U\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Zeigertypen.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Getesteter Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(const WeakPtr\<U\>\&) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Aufzählungstypen gegenüber schwachen Zeigern.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| U | Typ des referenzierten Objekts. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const WeakPtr\<U\>\& | [Object](../../object/) zum Testen des 'is'-Operators. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Is(int32_t) method


Implementiert die Übersetzung des 'is'-Operators. Spezialisierung für Integer-Literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int32_t | Ganzzahl-Literal. |

### ReturnValue

Wahr, wenn 'is' true zurückgibt, sonst false.

## Siehe auch

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
