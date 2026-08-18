---
title: "System::Char Klasse"
linktitle: "Char"
second_title: "Aspose.PUB für C++"
description: "System::Char Klasse. Stellt Methoden zur Manipulation von Zeichen bereit, die als UTF-16-Codeeinheiten dargestellt werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten unter keinen Umständen Instanzen davon in C++ erzeugen."
type: docs
weight: 1200
url: /de/cpp/system/char/
---
## Char class


Bietet Methoden zur Manipulation von Zeichen, die als UTF‑16‑Codeeinheiten dargestellt werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Char
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [ConvertFromUtf32](./convertfromutf32/)(uint32_t) | Konvertiert eine UTF-32-Codeeinheit in eine Instanz der [System::String](../string/) Klasse. |
| static [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Konvertiert das angegebene UTF-16-Surrogatpaar in eine UTF-32-Codeeinheit. |
| static [ConvertToUtf32](./converttoutf32/)(const String\&, int) | Konvertiert den Wert eines UTF-16-codierten Zeichens oder Surrogatpaars an einer angegebenen Position in einer Zeichenkette in eine UTF-32-Codeeinheit. |
| static [GetNumericValue](./getnumericvalue/)(char_t) | Konvertiert das angegebene UTF-16-Zeichen in einen double-präzisen Gleitkommawert. |
| static [GetUnicodeCategory](./getunicodecategory/)(char_t) | Gibt einen Wert zurück, der die Unicode-Kategorie des angegebenen Zeichens darstellt. |
| static [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Bestimmt, ob das angegebene Zeichen als ASCII-Leerzeichen klassifiziert ist. |
| static [IsControl](./iscontrol/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Steuerzeichen klassifiziert ist. |
| static [IsControl](./iscontrol/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Steuerzeichen klassifiziert ist. |
| static [IsDigit](./isdigit/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Dezimalziffer klassifiziert ist. |
| static [IsDigit](./isdigit/)(const String\&, const int32_t) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette als Dezimalziffer klassifiziert ist. |
| static [IsDigit](./isdigit/)(char_t) | Bestimmt, ob das angegebene Zeichen als Dezimalziffer klassifiziert ist. |
| static [IsHighSurrogate](./ishighsurrogate/)(const String\&, int) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette eine UTF-16-High-Surrogat-Codeeinheit ist. |
| static [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer ein High-Surrogat ist. |
| static [IsHighSurrogate](./ishighsurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen ein High-Surrogat ist. |
| static [IsLetter](./isletter/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Buchstabe klassifiziert ist. |
| static [IsLetter](./isletter/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Buchstabe klassifiziert ist. |
| static [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Buchstabe oder Dezimalziffer klassifiziert ist. |
| static [IsLetterOrDigit](./isletterordigit/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Buchstabe oder Dezimalziffer klassifiziert ist. |
| static [IsLower](./islower/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Kleinbuchstabe klassifiziert ist. |
| static [IsLower](./islower/)(char_t) | Bestimmt, ob das angegebene Zeichen als Kleinbuchstabe klassifiziert ist. |
| static [IsLower](./islower/)(const String\&, int) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette als Kleinbuchstabe klassifiziert ist. |
| static [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer ein Low-Surrogat ist. |
| static [IsLowSurrogate](./islowsurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen ein Low-Surrogat ist. |
| static [IsNumber](./isnumber/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Zahl klassifiziert ist. |
| static [IsNumber](./isnumber/)(char_t) | Bestimmt, ob das angegebene Zeichen als Zahl klassifiziert ist. |
| static [IsPunctuation](./ispunctuation/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Satzzeichen klassifiziert ist. |
| static [IsPunctuation](./ispunctuation/)(char_t) | Bestimmt, ob das angegebene Zeichen als Satzzeichen klassifiziert ist. |
| static [IsSeparator](./isseparator/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Trennzeichen klassifiziert ist. |
| static [IsSeparator](./isseparator/)(char_t) | Bestimmt, ob das angegebene Zeichen als Trennzeichen klassifiziert ist. |
| static [IsSurrogate](./issurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen eine UTF-16-Surrogat-Codeeinheit ist. |
| static [IsSurrogate](./issurrogate/)(const String\&, int) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette eine UTF-16-Surrogat-Codeeinheit ist. |
| static [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Bestimmt, ob die beiden angegebenen Zeichen ein UTF-16-Surrogat-Paar bilden. |
| static [IsSurrogatePair](./issurrogatepair/)(const String\&, int) | Bestimmt, ob zwei aufeinanderfolgende Zeichen im angegebenen Zeichenpuffer ein Surrogat-Paar bilden. |
| static [IsSymbol](./issymbol/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Symbolzeichen klassifiziert ist. |
| static [IsSymbol](./issymbol/)(char_t) | Bestimmt, ob das angegebene Zeichen als Symbolzeichen klassifiziert ist. |
| static [IsUpper](./isupper/)(const String\&, int) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette als Großbuchstabe klassifiziert ist. |
| static [IsUpper](./isupper/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Großbuchstabe klassifiziert ist. |
| static [IsUpper](./isupper/)(char_t) | Bestimmt, ob das angegebene Zeichen als Großbuchstabe klassifiziert ist. |
| static [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Leerzeichen klassifiziert ist. |
| static [IsWhiteSpace](./iswhitespace/)(char_t) | Bestimmt, ob das angegebene Zeichen als Leerzeichen klassifiziert ist. |
| static [IsWhiteSpace](./iswhitespace/)(const String\&, int) | Bestimmt, ob das Zeichen am angegebenen Index in der angegebenen Zeichenkette als Leerzeichen klassifiziert ist. |
| static [Parse](./parse/)(const String\&) | Konvertiert das erste und einzige Zeichen der angegebenen Zeichenkette in einen char_t-Wert. |
| static [ToLower](./tolower/)(char_t) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static [ToLower](./tolower/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static [ToLowerInvariant](./tolowerinvariant/)(char_t) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static [ToUpper](./toupper/)(char_t) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static [ToUpper](./toupper/)(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static [ToUpperInvariant](./toupperinvariant/)(char_t) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static [TryParse](./tryparse/)(const System::String\&, char_t\&) | Versucht, eine Zeichenkette, die aus einem einzelnen Zeichen besteht, in ein UTF-16-Zeichen zu konvertieren. Die Funktion ist nur erfolgreich, wenn die Eingabezeichenkette nicht null ist und genau ein Zeichen lang ist. |
## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
