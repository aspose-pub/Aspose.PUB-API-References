---
title: "System::String::Equals Methode"
linktitle: "Equals"
second_title: "Aspose.PUB für C++"
description: "System::String::Equals Methode. Vergleich von Zeichenketten auf Gleichheit. Verwendet den Vergleichsmodus System::StringComparison::Ordinal in C++."
type: docs
weight: 1000
url: /de/cpp/system/string/equals/
---
## String::Equals(const String\&) const method


[String](../) equality comparison. Uses [System::StringComparison::Ordinal](../../stringcomparison/) comparison mode.

```cpp
bool System::String::Equals(const String &str) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | [String](../) zum Vergleich mit der aktuellen. |

### ReturnValue

wahr, wenn Zeichenketten übereinstimmen, sonst falsch.

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Equals(const String\&, System::StringComparison) const method


[String](../) equality comparison. Several modes provided by StringComparison enumeration are supported.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | [String](../) zum Vergleich mit der aktuellen. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) Modus (siehe [System::StringComparison](../../stringcomparison/) für Details). |

### ReturnValue

true, wenn Zeichenketten mit dem ausgewählten Vergleichstyp übereinstimmen, sonst false.

## Siehe auch

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Equals(const String\&, const String\&) method


Equal vergleicht zwei Zeichenketten im Ordinal-Vergleichsmodus.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const String\& | Erste Zeichenkette zum Vergleichen. |
| strB | const String\& | Zweite Zeichenkette zum Vergleichen. |

### ReturnValue

wahr, wenn Zeichenketten übereinstimmen, sonst falsch.

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Equals(const String\&, const String\&, System::StringComparison) method


Equal vergleicht zwei Zeichenketten.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const String\& | Erste Zeichenkette zum Vergleichen. |
| strB | const String\& | Zweite Zeichenkette zum Vergleichen. |
| comparison_type | System::StringComparison | [Comparison](../../comparison/) Modus. |

### ReturnValue

wahr, wenn Zeichenketten übereinstimmen, sonst falsch.

## Siehe auch

* Class [String](../)
* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
