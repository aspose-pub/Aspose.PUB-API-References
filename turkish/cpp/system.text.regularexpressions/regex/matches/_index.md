---
title: "System::Text::RegularExpressions::Regex::Matches method"
linktitle: "Eşleşmeler"
second_title: "Aspose.PUB için C++"
description: "System::Text::RegularExpressions::Regex::Matches method. C++'da tekrar tekrar eşleştirerek verilen dizedeki tüm regex eşleşmelerini alır."
type: docs
weight: 700
url: /tr/cpp/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Verilen dizede düzenli ifadenin tüm eşleşmelerini tekrar tekrar eşleştirerek alır.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Girdi dizesi. |
| startat | int | Eşleştirmenin başlayacağı indeks. |

### ReturnValue

Bulunan tüm eşleşmelerin koleksiyonu.

## Ayrıca Bakınız

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Dize ve desen arasındaki tüm eşleşmeleri alır.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
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

Tekrar tekrar eşleştirerek bulunan tüm eşleşmeler.

## Ayrıca Bakınız

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
