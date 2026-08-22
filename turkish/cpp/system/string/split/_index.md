---
title: "System::String::Split yöntemi"
linktitle: "Böl"
second_title: "Aspose.PUB için C++"
description: "System::String::Split yöntemi. Dizeyi C++'ta karaktere göre böler."
type: docs
weight: 4100
url: /tr/cpp/system/string/split/
---
## String::Split(char_t, int32_t, StringSplitOptions) const method


Dizeyi karaktere göre böler.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | char_t | Dizeyi bölecek karakter. |
| sayım | int32_t | Döndürülecek azami alt dize sayısı. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(char_t, StringSplitOptions) const method


Dizeyi karaktere göre böler.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | char_t | Dizeyi bölecek karakter. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(char_t, char_t, StringSplitOptions) const method


Dizeyi iki karakterden birine göre bölür.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorA | char_t | Dizeyi bölecek ilk karakter. |
| separatorB | char_t | Dizeyi bölmek için ikinci karakter. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method


Dizeyi belirtilen karakterlerden birine göre bölür.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) ayırıcı karakterler. Boş ise, herhangi bir boşluk karakteri ayırıcı olarak kabul edilir. |
| sayım | int32_t | Döndürülecek azami alt dize sayısı. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method


Dizeyi belirtilen karakterlerden birine göre bölür.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const ArrayPtr\<char_t\>\& | [Array](../../array/) ayırıcı karakterler. Boş ise, herhangi bir boşluk karakteri ayırıcı olarak kabul edilir. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method


Dizeyi alt dizeye göre bölür. Şu anda yalnızca sıfır veya bir öğe içeren ayırıcılar dizisini destekler.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) ayırıcı dizgeler. Boş ise, bölme işlemi yapılmaz. |
| sayım | int | Bölünmüş dizi içindeki azami öğe sayısı. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method


Dizeyi alt dizeye göre bölür.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separators | const ArrayPtr\<String\>\& | [Array](../../array/) ayırıcı dizgeler. Boş ise, bölme işlemi yapılmaz. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const String\&, int, StringSplitOptions) const method


Dizeyi alt dizeye göre bölür.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const String\& | Ayırıcı olarak kullanılan alt dize. Boş ise, boşluk karakteri ayırıcı olarak kullanılır. |
| sayım | int | Bölünmüş dizi içindeki azami öğe sayısı. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::Split(const String\&, StringSplitOptions) const method


Dizeyi alt dizeye göre bölür.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separator | const String\& | Ayırıcı olarak kullanılan alt dize. Boş ise, boşluk karakteri ayırıcı olarak kullanılır. |
| opt | StringSplitOptions | Bölme seçenekleri. |

### ReturnValue

[Array](../../array/) of substrings.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Enum [StringSplitOptions](../../stringsplitoptions/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
