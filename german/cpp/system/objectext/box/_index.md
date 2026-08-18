---
title: "System::ObjectExt::Box Methode"
linktitle: "Box"
second_title: "Aspose.PUB für C++"
description: "System::ObjectExt::Box Methode. Verpackt Zeichenkettenwerte in C++."
type: docs
weight: 200
url: /de/cpp/system/objectext/box/
---
## ObjectExt::Box(const String\&) method


Boxt Zeichenkettenwerte.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const String\& | Wert zum Boxen. |

### ReturnValue

Geboxter Wert oder null, falls die Quellzeichenkette null ist.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxt Werttypen für die Konvertierung zu [Object](../../object/). Implementierung für Enum-Typen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beschreibung |
| --- | --- |
| T | [Enum](../../enum/) Typ. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) Wert zum Boxen. |

### ReturnValue

Smart-Pointer zu Objekt, das den geboxten Wert hält.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxt Werttypen für die Konvertierung zu [Object](../../object/). Implementierung für Nicht-Enum-Typen.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | Wert zum Boxen. |

### ReturnValue

Smart-Pointer zu Objekt, das den geboxten Wert hält.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::Box(const T\&) method


Boxt [Nullable](../../nullable/) Typen für die Konvertierung zu [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | Wert zum Boxen. |

### ReturnValue

Smart-Pointer zu Objekt, das den geboxten Wert hält.

## Siehe auch

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
