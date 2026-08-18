---
title: "System::String::Split Methode"
linktitle: "Split"
second_title: "Aspose.PUB für C++"
description: "System::String::Split Methode. Teilt den String nach Zeichen in C++."
type: docs
weight: 4100
url: /de/cpp/system/string/split/
---
## String::Split(char_t, int32_t, StringSplitOptions) const method


Teilt die Zeichenkette nach Zeichen.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Trennzeichen | char_t | Zeichen, nach dem der String geteilt wird. |
| Anzahl | int32_t | Die maximale Anzahl zurückzugebender Teilstrings. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(char_t, StringSplitOptions) const method


Teilt die Zeichenkette nach Zeichen.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Trennzeichen | char_t | Zeichen, nach dem der String geteilt wird. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(char_t, char_t, StringSplitOptions) const method


Teilt die Zeichenkette nach einem von zwei Zeichen.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorA | char_t | Erstes Zeichen, nach dem der String geteilt wird. |
| separatorB | char_t | Zweites Zeichen, nach dem der String geteilt wird. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method


Teilt die Zeichenkette nach einem der angegebenen Zeichen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Trennzeichen. Wenn leer, wird jedes Leerzeichen als Trennzeichen betrachtet. |
| Anzahl | int32_t | Die maximale Anzahl zurückzugebender Teilstrings. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method


Teilt die Zeichenkette nach einem der angegebenen Zeichen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) von Trennzeichen. Wenn leer, wird jedes Leerzeichen als Trennzeichen betrachtet. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method


Teilt Zeichenkette nach Teilzeichenkette. Derzeit werden nur Trennzeichen‑Arrays mit null oder einem Element unterstützt.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) von Trennzeichen-Strings. Wenn leer, wird keine Aufteilung durchgeführt. |
| Anzahl | int | Maximale Anzahl von Elementen im Splits-Array. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method


Teilt Zeichenkette nach Teilzeichenkette.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) von Trennzeichen-Strings. Wenn leer, wird keine Aufteilung durchgeführt. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const String\&, int, StringSplitOptions) const method


Teilt Zeichenkette nach Teilzeichenkette.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Trennzeichen | const String\& | Teilzeichenfolge, die als Trennzeichen fungiert. Wenn leer, wirkt das Leerzeichen als Trennzeichen. |
| Anzahl | int | Maximale Anzahl von Elementen im Splits-Array. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const String\&, StringSplitOptions) const method


Teilt Zeichenkette nach Teilzeichenkette.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Trennzeichen | const String\& | Teilzeichenfolge, die als Trennzeichen fungiert. Wenn leer, wirkt das Leerzeichen als Trennzeichen. |
| opt | StringSplitOptions | Teilungsoptionen. |

### ReturnValue

[Array](../../array/) of substrings.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
