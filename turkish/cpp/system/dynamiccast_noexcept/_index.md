---
title: "System::DynamicCast_noexcept method"
linktitle: "DynamicCast_noexcept"
second_title: "Aspose.PUB için C++"
description: "System::DynamicCast_noexcept method. Eski, kullanımdan kaldırılmış dönüşümler. C++'da gelecekteki sürümlerde kaldırılacak."
type: docs
weight: 16500
url: /tr/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Eski, kullanımdan kaldırılmış dönüşümler. Gelecek sürümlerde kaldırılacak.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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
## Açıklamalar


Exception nesneleri üzerinde dinamik dönüşüm gerçekleştirir. ## Kullanımdan Kaldırıldı
Geriye dönük uyumluluk için bırakılmıştır. Bunun yerine AsCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


[SmartPtr](../smartptr/) nesneleri üzerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Nesneleri Exception nesnelerine dinamik olarak dönüştürür.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
