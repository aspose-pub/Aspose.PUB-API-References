---
title: "System::DynamicCast metodu"
linktitle: "DynamicCast"
second_title: "Aspose.PUB için C++"
description: "System::DynamicCast metodu. C++'ta Exception nesneleri üzerinde dinamik dönüşüm gerçekleştirir."
type: docs
weight: 15800
url: /tr/cpp/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) method


Exception nesneleri üzerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\> const\&) method


[SmartPtr](../smartptr/) nesneleri üzerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\>) method


Kutulanmış enum'u dönüşüm yoluyla kutudan çıkarır.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef enum türü. |
| TFrom | Kaynak işaret edilen tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Veri çıkarılacak nesneye işaretçi. |

### ReturnValue

Kutudan çıkarılmış enum değeri.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\>) method


Nesneleri Exception nesnelerine dinamik olarak dönüştürür.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
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
## System::DynamicCast(std::nullptr_t) method


Null nesneler üzerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
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
## System::DynamicCast(TFrom\&) method


İşaretçi olmayan nesneler üzerinde dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tip. |
| TFrom | Kaynak tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | TFrom\& | Kaynak nesne. |

### ReturnValue

Dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
## System::DynamicCast(TFrom) method


IntPtr'ten işaretçiye dinamik dönüşüm gerçekleştirir.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


| Parametre | Açıklama |
| --- | --- |
| TTo | Hedef tip. |
| TFrom | Kaynak tip. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | TFrom | Kaynak IntPtr değeri. |

### ReturnValue

Dönüşüm sonucu.

## Deprecated
Geriye dönük uyumluluk için bırakıldı. Bunun yerine ExplicitCast kullanın.

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
