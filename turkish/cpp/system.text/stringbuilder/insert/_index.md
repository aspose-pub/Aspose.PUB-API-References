---
title: "System::Text::StringBuilder::Insert yöntemi"
linktitle: "Ekle"
second_title: "Aspose.PUB için C++"
description: "System::Text::StringBuilder::Insert yöntemi. C++'da karakterleri builder'ın sabit konumuna ekler."
type: docs
weight: 1200
url: /tr/cpp/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) method


Karakterleri yapıcının sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Karakterlerin ekleneceği konum. |
| chars | const System::ArrayPtr\<char_t\>\& | [Array](../../../system/array/) dilimini eklemek için. |
| startIndex | int | [Array](../../../system/array/) diliminin başlangıç indeksi. |
| charCount | int | [Array](../../../system/array/) diliminin uzunluğu. |

### ReturnValue

Bu gösterici.

## Ayrıca Bakınız

* Class [StringBuilder](../)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## StringBuilder::Insert(int, char_t) method


Karakteri yapıcının sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| ch | char_t | Eklenecek karakter. |

### ReturnValue

Bu gösterici.

## Ayrıca Bakınız

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## StringBuilder::Insert(int, const String\&) method


Dizeyi yapıcının sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| str | const String\& | [String](../../../system/string/) eklemek için. |

### ReturnValue

Bu gösterici.

## Ayrıca Bakınız

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## StringBuilder::Insert(int, T) method


Değeri yapıcının sabit konumuna ekler.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


| Parametre | Açıklama |
| --- | --- |
| Parametre | tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Karakterlerin ekleneceği konum. |
| değer | T | Biçimlendirilip eklenecek değer. |

### ReturnValue

Bu gösterici.

## Ayrıca Bakınız

* Class [StringBuilder](../)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
## StringBuilder::Insert(int32_t, const String\&, int32_t) method


Tekrarlanan dizeyi yapıcının sabit konumuna ekler.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int32_t | Karakterlerin ekleneceği konum. |
| value | const String\& | [String](../../../system/string/) eklemek için. |
| sayım | int32_t | **value** dizesinin kaç kez tekrarlanacağı. |

### ReturnValue

Bu gösterici.

## Ayrıca Bakınız

* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [StringBuilder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PUB for C++](../../../)
