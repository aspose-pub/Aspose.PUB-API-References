---
title: "System::Text::RegularExpressions::Regex::Match metodu"
linktitle: "Match"
second_title: "Aspose.PUB için C++"
description: "System::Text::RegularExpressions::Regex::Match metodu. C++'ta regex'i dizeye karşı eşleştirir."
type: docs
weight: 600
url: /tr/cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Düzenli ifadeyi dizeye karşı eşleştirir.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Hedef dize. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Ayrıca Bakınız

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Match(const String\&, int, int) method


Düzenli ifadeyi dizeye karşı eşleştirir.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Hedef dize. |
| startat | int | Başlangıç indeksi. |
| uzunluk | int | İncelenecek karakter sayısı (tam dizeyi incelemek için 0). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Ayrıca Bakınız

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Dizeyi ve deseni eşleştirir.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Girdi dizesi. |
| desen | const String\& | Regexp deseni. |
| seçenekler | RegexOptions | Eşleştirme seçenekleri. |
| matchTimeout | TimeSpan | Zaman aşımı. |
| startat | int | [Match](../../match/) başlangıç konumu. |
| uzunluk | int | İncelenecek karakter sayısı (0 sınırlamayı devre dışı bırakır). |

### ReturnValue

Bulunan ilk eşleşme.

## Ayrıca Bakınız

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
