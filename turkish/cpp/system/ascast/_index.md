---
title: "System::AsCast yöntemi"
linktitle: "AsCast"
second_title: "Aspose.PUB için C++"
description: "System::AsCast yöntemi. Kaynak tipi, ''as'' operatör dönüşümü kullanarak sonuç tipine dönüştürür. C++'ta basit yapıcı benzeri dönüşüm gerektiğinde kullanılır."
type: docs
weight: 12900
url: /tr/cpp/system/ascast/
---
## System::AsCast(const Source\&) method


Kaynak tipini, 'as' operatör dönüşümü kullanarak sonuç tipine dönüştürür. Basit yapıcı benzeri dönüşüm gerektiğinde kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak tipini, 'as' operatör dönüşümü kullanarak sonuç tipine dönüştürür. Kaynak ve sonuç tipleri aynı olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak tipini, 'as' operatör dönüşümü kullanarak sonuç tipine dönüştürür. İstisna sarmalayıcıları için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Dönüşüm mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak tipini, 'as' operatör dönüşümü kullanarak sonuç tipine dönüştürür. Nesneyi istisna olarak dönüştürmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Dönüşüm mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak tipini, 'as' operatör dönüşümü kullanarak sonuç tipine dönüştürür. Kaynak ve sonuç her ikisi de akıllı işaretçi olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Dönüşüm mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Kaynak ve sonucun her ikisi de akıllı işaretçiler olduğunda (sonuç türünde açıkça SmartPtr<...> ile) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Dönüşüm mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Nesneyi nullable'a ayıklamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Dönüşüm mevcut değilse boş nullable döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Nesne olmayan tipe geçersiz ayıklama.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Her zaman null döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Nullable nesneyi kutulamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Genel nesneyi kutulamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Dizeyi ayıklamak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. nullptr durumunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::AsCast(const Source\&) method


Kaynak türü, 'as' operatör dönüşümü kullanarak sonuç türüne dönüştürür. Diziler arasında dönüşüm yapmak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const Source\& | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu. Herhangi bir dizi üyesi için dönüşüm mevcut değilse nullptr döndürür.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
