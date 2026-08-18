---
title: "System::String::String Konstruktor"
linktitle: "String"
second_title: "Aspose.PUB für C++"
description: "System::String::String Konstruktor. Standardkonstruktor. Erstellt ein String-Objekt, das in C++ als null betrachtet wird."
type: docs
weight: 100
url: /de/cpp/system/string/string/
---
## String::String() constructor


Standardkonstruktor. Erstellt ein Zeichenkettenobjekt, das als null betrachtet wird.

```cpp
System::String::String()
```

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(codeporting_icu::UnicodeString\&&) constructor


Move‑Konstruktor.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString, um in [String](../) zu verpacken. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&) constructor


Konvertiert das gesamte Zeichen‑Array in eine Zeichenkette.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | [Array](../../array/) zum Konvertieren in einen String. |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor


Konvertiert einen Teilbereich eines Zeichen‑Arrays in eine Zeichenkette. Wenn Parameter außerhalb der Array‑Grenzen liegen, wird eine leere Zeichenkette erstellt.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | Zeichenarray. |
| Versatz | int | Startindex des Teilarrays. |
| len | int | Länge des Teilarrays. |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char *, int) constructor


Konstruiert Zeichenkette aus einem Zeiger auf eine Zeichenkette und einer expliziten Länge.

```cpp
System::String::String(const char *str, int length)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char * | [String](../) Zeiger auf die UTF8-Daten, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t *, int) constructor


Konstruiert Zeichenkette aus einem Zeiger auf eine Zeichenkette und einer expliziten Länge.

```cpp
System::String::String(const char16_t *str, int length)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t *, int, int) constructor


Konstruiert Zeichenkette aus einem Zeiger auf eine Zeichenkette ab einer Startposition unter Verwendung einer Länge.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| start | int | Startposition. |
| length | int | [String](../) Länge. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t, int) constructor


Füllkonstruktor.

```cpp
System::String::String(const char16_t ch, int count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | const char16_t | Füllzeichen. |
| Anzahl | int | Ziel-Länge. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const codeporting_icu::UnicodeString\&) constructor


Packt UnicodeString in [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString, um in [String](../) zu verpacken. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::string\&) constructor


Erstellt [String](../) aus einem std::string, der im UTF-8-Format vorliegt.

```cpp
System::String::String(const std::string &utf8str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| utf8str | const std::string\& | std::string, der in [String](../) konvertiert werden soll. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::u16string\&) constructor


Erstellt [String](../) aus einem utf16-String.

```cpp
System::String::String(const std::u16string &str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const std::u16string\& | Utf16-String, der in [String](../) konvertiert werden soll. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::u32string\&) constructor


Erstellt [String](../) aus einem std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string, der in [String](../) konvertiert werden soll. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::wstring\&) constructor


Erstellt [String](../) aus einem Wide-String.

```cpp
System::String::String(const std::wstring &str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const std::wstring\& | Wide-String, der in [String](../) konvertiert werden soll. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const String\&) constructor


Kopierkonstruktor.

```cpp
System::String::String(const String &str)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const String\& | [String](../) zum Kopieren. |

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem Zeiger auf eine Zeichenkette. Behandelt die referenzierte Zeichenkette als nullterminiert in UTF‑8 und berechnet die Zielzeichenkettenlänge anhand des Null‑Zeichens.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | Zeiger auf Zeichenkette. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem Zeiger auf eine Zeichenkette. Behandelt die referenzierte Zeichenkette als nullterminiert und berechnet die Zielzeichenkettenlänge anhand des Null‑Zeichens.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | Zeiger auf Zeichenkette. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem Zeiger auf eine Wide‑Character‑Zeichenkette. Behandelt die referenzierte Zeichenkette als nullterminiert und berechnet die Zielzeichenkettenlänge anhand des Null‑Zeichens. Die Konvertierung von wchar_t ist auf einigen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | Zeiger auf Zeichenkette. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Nullptr‑Konstruktor. Als Template deklariert, um Prioritäten mit anderen Template‑Konstruktoren aufzulösen.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


| Parameter | Beschreibung |
| --- | --- |
| T | Sollte nullptr_t sein |

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | const T\& | nullptr |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const wchar_t *, int) constructor


Konstruiert Zeichenkette aus einem Zeiger auf eine Wide‑Character‑Zeichenkette und einer expliziten Länge. Die Konvertierung von wchar_t ist auf einigen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
System::String::String(const wchar_t *str, int length)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const wchar_t * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const wchar_t, int) constructor


Füllkonstruktor. Die Konvertierung von wchar_t ist auf einigen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | const wchar_t | Füllzeichen. |
| Anzahl | int | Ziel-Länge. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(String\&&) constructor


Move‑Konstruktor.

```cpp
System::String::String(String &&str) noexcept
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | String\&& | [String](../) zum Verschieben von Daten. |

## Siehe auch

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem String‑Literal. Betrachtet das Literal als nullterminierte Zeichenkette in UTF‑8 und berechnet die Zielzeichenkettenlänge anhand der Literalgröße.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../)-Literalzeiger. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem String‑Literal. Betrachtet das Literal als nullterminierte Zeichenkette und berechnet die Zielzeichenkettenlänge anhand der Literalgröße.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../)-Literalzeiger. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor


Konstruiert Zeichenkette basierend auf einem Wide‑String‑Literal. Betrachtet das Literal als nullterminierte Zeichenkette und berechnet die Zielzeichenkettenlänge anhand der Literalgröße. Die Konvertierung von wchar_t ist auf einigen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../)-Literalzeiger. |

## Siehe auch

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
