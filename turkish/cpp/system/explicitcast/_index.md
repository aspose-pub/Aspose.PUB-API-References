---
title: "System::ExplicitCast yöntemi"
linktitle: "ExplicitCast"
second_title: "Aspose.PUB için C++"
description: "System::ExplicitCast yöntemi. Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. C++'da kaynak ve sonuç türleri aynı olduğunda kullanılır."
type: docs
weight: 17400
url: /tr/cpp/system/explicitcast/
---
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Kaynak ve sonuç türleri aynı olduğunda kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Basit yapıcı benzeri dönüştürme gerektiğinde kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. İstisna sarmalayıcıları için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
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

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Nesneyi istisna olarak dönüştürmek için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Kaynak ve sonuç her ikisi de akıllı işaretçi olduğunda (sonuç türünde açık SmartPtr<...> olmadan) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Kaynak ve sonuç her ikisi de akıllı işaretçi olduğunda (sonuç türünde açık SmartPtr<...> ile) kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Nesneyi nullable tipe kutudan çıkarma (unboxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Nullable'ı kutuya (boxing) almak için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Nullable nesneyi kutudan çıkarma için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Enum kutulama (boxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
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

* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Genel kutulama (boxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. [System::String](../string/) kutulama için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Genel kutudan çıkarma (unboxing) için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. nullptr dönüştürmesi için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(const Source\&) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Diziler arasında dönüştürme için kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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
## System::ExplicitCast(Source) method


Kaynak türünü sonuç türüne açık dönüştürme kullanarak dönüştürür. Ham işaretçiyi akıllı işaretçiye dönüştürürken kullanılır.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


| Parametre | Açıklama |
| --- | --- |
| Kaynak | Kaynak tipi. |
| Sonuç | Sonuç tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | Source | Dönüştürülecek [Object](../object/). |

### ReturnValue

Dönüşüm sonucu.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
