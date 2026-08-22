---
title: "System::Text::RegularExpressions::Regex::Split metodu"
linktitle: "Böl"
second_title: "Aspose.PUB için C++"
description: "System::Text::RegularExpressions::Regex::Split metodu. C++'ta regex eşleşmelerine göre dizeyi böler."
type: docs
weight: 900
url: /tr/cpp/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) method


Dizeyi düzenli ifade eşleşmelerine göre böler.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) bölmek için. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, int) method


Dizeyi düzenli ifade eşleşmelerine göre böler.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | [String](../../../system/string/) bölmek için. |
| sayım | int | Alt dizelerin sayısı sınırı. |

### ReturnValue

[Array](../../../system/array/) of substrings between matches.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, int, int) method


Giriş dizesini, [Regex](../) yapıcısında belirtilen bir düzenli ifadeyle tanımlanan konumlardan, belirtilen azami sayıda kez alt dize dizisine böler. Düzenli ifade deseninin aranması, giriş dizesindeki belirtilen karakter konumundan başlar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Bölünecek dize. |
| sayım | int | Bölmenin gerçekleşebileceği azami sayı. |
| startat | int | Aramanın başlayacağı giriş dizesindeki karakter konumu. |

### ReturnValue

Dizeler dizisi.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) method


Dizeyi regexp ile böler.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Girdi dizesi. |
| desen | const String\& | Regexp deseni. |
| count | int | [Match](../../match/) sayı sınırı. |
| seçenekler | RegexOptions | Eşleştirme seçenekleri. |
| matchTimeout | TimeSpan | Zaman aşımı. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) method


Dizeyi regexp ile böler.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const String\& | Girdi dizesi. |
| desen | const String\& | Regexp deseni. |
| seçenekler | RegexOptions | Eşleştirme seçenekleri. |
| matchTimeout | TimeSpan | Zaman aşımı. |

### ReturnValue

[Array](../../../system/array/) of strings between matchse.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PUB for C++](../../../)
