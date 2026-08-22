---
title: "System::StaticCast yöntemi"
linktitle: "StaticCast"
second_title: "Aspose.PUB için C++"
description: "System::StaticCast yöntemi. C++'ta işaretçi olmayan nesneler üzerinde statik dönüşüm gerçekleştirir."
type: docs
weight: 35000
url: /tr/cpp/system/staticcast/
---
## System::StaticCast(const TFrom\&) method


İşaretçi olmayan nesneler üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tip. |
| TFrom | Kaynak tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak nesne. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(const TFrom\&) method


Exception nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | Kaynak Exception türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak işaretçi. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(const TFrom *) method


Aritmetik tipler için özelleştirme.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\> const\&) method


[SmartPtr](../smartptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\>) method


Objects nesnelerini Exception nesnelerine statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | [Object](../object/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Kaynak işaretçi. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(std::nullptr_t) method


Null nesneler üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |

### ReturnValue

nullptr.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(TFrom) method


Aritmetik tipler için özelleştirme.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(TTo) method


[String](../string/) tipinden [String](../string/) tipine dönüşümü işle.

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## Ayrıca Bakınız

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast(WeakPtr\<TFrom\> const\&) method


[WeakPtr](../weakptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüşüm izinliyse dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
