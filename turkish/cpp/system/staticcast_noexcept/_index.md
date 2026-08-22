---
title: "System::StaticCast_noexcept method"
linktitle: "StaticCast_noexcept"
second_title: "Aspose.PUB için C++"
description: "System::StaticCast_noexcept method. C++'da Exception nesneleri üzerinde statik dönüşüm gerçekleştirir."
type: docs
weight: 35900
url: /tr/cpp/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(const TFrom\&) method


Exception nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | Kaynak Exception türü. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const TFrom\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.

## Deprecated
Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) method


[SmartPtr](../smartptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.

## Deprecated
Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\>) method


Objects nesnelerini Exception nesnelerine statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef Exception türü. |
| TFrom | [Object](../object/) tipi. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.

## Deprecated
Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) method


[WeakPtr](../weakptr/) nesneleri üzerinde statik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef işaret edilen tip. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Kaynak işaretçi. |

### ReturnValue

Dönüştürme izinliyse dönüş sonucu, aksi takdirde nullptr.

## Deprecated
Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
