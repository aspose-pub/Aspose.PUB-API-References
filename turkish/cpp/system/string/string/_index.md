---
title: "System::String::String yapıcı"
linktitle: "String"
second_title: "Aspose.PUB için C++"
description: "System::String::String yapıcı. Varsayılan yapıcı. C++'ta null olarak kabul edilen bir dize nesnesi oluşturur."
type: docs
weight: 100
url: /tr/cpp/system/string/string/
---
## String::String() constructor


Varsayılan yapıcı. Null olarak kabul edilen bir dize nesnesi oluşturur.

```cpp
System::String::String()
```

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(codeporting_icu::UnicodeString\&&) constructor


Taşıma yapıcı.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString'ı [String](../) içine sarmak için. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&) constructor


Tüm karakter dizisini dizeye dönüştürür.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | [Array](../../array/) dizeye dönüştürmek için. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor


Karakter dizisinin alt aralığını dizeye dönüştürür. Parametreler dizi sınırları dışındaysa, boş bir dize oluşturulur.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const ArrayPtr\<char16_t\>\& | Karakter dizisi. |
| ofset | int | Alt dizi başlangıç indeksi. |
| len | int | Alt dizi uzunluğu. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char *, int) constructor


Dizeyi karakter dize işaretçisinden ve açık uzunluktan oluşturur.

```cpp
System::String::String(const char *str, int length)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char * | [String](../) UTF8 verisine işaretçi, literal veya dizi olabilir. |
| uzunluk | int | Açık dize uzunluğu |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t *, int) constructor


Dizeyi karakter dize işaretçisinden ve açık uzunluktan oluşturur.

```cpp
System::String::String(const char16_t *str, int length)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../) işaretçisi, literal veya dizi olabilir. |
| uzunluk | int | Açık dize uzunluğu |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t *, int, int) constructor


Dizeyi karakter dize işaretçisinden başlangıç konumundan uzunluk kullanarak oluşturur.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../) işaretçisi, literal veya dizi olabilir. |
| başlangıç | int | Başlangıç konumu. |
| length | int | [String](../) uzunluğu. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const char16_t, int) constructor


Doldurma yapıcı.

```cpp
System::String::String(const char16_t ch, int count)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | const char16_t | Doldurma karakteri. |
| sayım | int | Hedef uzunluk. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const codeporting_icu::UnicodeString\&) constructor


UnicodeString'i [String](../) içine sarar.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString'ı [String](../) içine sarmak için. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::string\&) constructor


UTF-8 formatında sunulan std::string dizesinden [String](../) oluşturur.

```cpp
System::String::String(const std::string &utf8str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| utf8str | const std::string\& | std::string dizesi, [String](../)'a dönüştürülmek üzere. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::u16string\&) constructor


utf16 dizesinden [String](../) oluşturur.

```cpp
System::String::String(const std::u16string &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 dizesi, [String](../)'a dönüştürülmek üzere. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::u32string\&) constructor


std::u32string dizesinden [String](../) oluşturur.

```cpp
System::String::String(const std::u32string &u32str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string dizesi, [String](../)'a dönüştürülmek üzere. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const std::wstring\&) constructor


widestring'den [String](../) oluşturur.

```cpp
System::String::String(const std::wstring &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const std::wstring\& | Widestring, [String](../)'a dönüştürülmek üzere. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const String\&) constructor


Kopya yapıcı.

```cpp
System::String::String(const String &str)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const String\& | [String](../) kopyalamak için. |

## Ayrıca Bakınız

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor


Dizeyi karakter dize işaretçisine göre oluşturur. İşaret edilen dizeyi UTF8'de null sonlu olarak kabul eder, hedef dize uzunluğunu null karakterine göre hesaplar.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | Karakter dize işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor


Dizeyi karakter dize işaretçisine göre oluşturur. İşaret edilen dizeyi null sonlu olarak kabul eder, hedef dize uzunluğunu null karakterine göre hesaplar.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | Karakter dize işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor


Dizeyi geniş karakter dize işaretçisine göre oluşturur. İşaret edilen dizeyi null sonlu olarak kabul eder, hedef dize uzunluğunu null karakterine göre hesaplar. wchar_t dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | Karakter dize işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor


Nullptr yapıcı. Diğer şablon yapıcılarla öncelikleri çözmek için şablon olarak bildirilir.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


| Parametre | Açıklama |
| --- | --- |
| T | nullptr_t olmalı |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | const T\& | nullptr |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const wchar_t *, int) constructor


Dizeyi geniş karakter dize işaretçisinden ve açık uzunluktan oluşturur. wchar_t dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
System::String::String(const wchar_t *str, int length)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const wchar_t * | [String](../) işaretçisi, literal veya dizi olabilir. |
| uzunluk | int | Açık dize uzunluğu |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(const wchar_t, int) constructor


Doldurma yapıcı. wchar_t dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | const wchar_t | Doldurma karakteri. |
| sayım | int | Hedef uzunluk. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(String\&&) constructor


Taşıma yapıcı.

```cpp
System::String::String(String &&str) noexcept
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | String\&& | [String](../) verileri taşımak için. |

## Ayrıca Bakınız

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor


Dizeyi dize sabiti temel alarak oluşturur. Sabiti UTF8'de null sonlu bir dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor


Dizeyi dize sabiti temel alarak oluşturur. Sabiti null sonlu bir dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor


Dizeyi geniş dize sabiti temel alarak oluşturur. Sabiti null sonlu bir dize olarak kabul eder, hedef dize uzunluğunu sabit boyutuna göre hesaplar. wchar_t dönüşümü bazı platformlarda zaman alıcıdır, bu yüzden örtük dönüşümlere izin verilmez.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T\& | [String](../) literal işaretçisi. |

## Ayrıca Bakınız

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
