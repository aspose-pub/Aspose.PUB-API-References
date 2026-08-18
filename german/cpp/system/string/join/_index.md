---
title: "Methode System::String::Join"
linktitle: "Join"
second_title: "Aspose.PUB für C++"
description: "System::String::Join-Methode. Fügt ein Array zusammen, wobei ein String als Trennzeichen in C++ verwendet wird."
type: docs
weight: 7100
url: /de/cpp/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


Verbindet ein Array unter Verwendung des Strings als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const String\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const ArrayPtr\<SharedPtr\<Object\>\>\& | [Array](../../array/) von Teilen, die zusammengeführt werden sollen. |

### ReturnValue

[String](../) representing joint elements.

## Siehe auch

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


Verbindet ein Array unter Verwendung des Strings als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const String\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| parts | const ArrayPtr\<String\>\& | [Array](../../array/) von Teilen, die zusammengeführt werden sollen. |
| startIndex | int | Erster Index im Array, ab dem das Zusammenführen beginnt. |
| Anzahl | int | Anzahl der Array-Elemente, die zusammengeführt werden sollen. -1 bedeutet 'bis zum Ende des Arrays'. |

### ReturnValue

[String](../) representing joint array elements.

## Siehe auch

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


Verbindet ein Array unter Verwendung des Strings als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const String\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| Teile | const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\& | - aufzählbares Objekt von Teilen |

### ReturnValue

[String](../) representing joint elements.

## Siehe auch

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


Verbindet ein Array unter Verwendung des Strings als Trennzeichen.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const String\& | [String](../) zum Einfügen zwischen Array-Elementen beim Zusammenführen. |
| Teile | const System::Details::ArrayView\<String\>\& | ArrayView von Teilen, die zusammengeführt werden sollen. |
| startIndex | int | Erster Index im Array, ab dem das Zusammenführen beginnt. |
| Anzahl | int | Anzahl der Array-Elemente, die zusammengeführt werden sollen. -1 bedeutet 'bis zum Ende des Arrays'. |

### ReturnValue

[String](../) representing joint array elements.

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
