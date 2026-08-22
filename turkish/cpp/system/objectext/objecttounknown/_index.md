---
title: "System::ObjectExt::ObjectToUnknown method"
linktitle: "ObjectToUnknown"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::ObjectToUnknown method. Object'i bilinmeyen bir türe dönüştürür, C++'ta hem akıllı işaretçi türünü hem de kutulanmış değer durumlarını ele alır."
type: docs
weight: 1200
url: /tr/cpp/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


[Object](../../object/) öğesini bilinmeyen bir türe dönüştürür, hem akıllı işaretçi türünü hem de kutulanmış değer durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/) öğesini dönüştürmek için hedef tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | Dönüştürülecek [Object](../../object/). |

### ReturnValue

Açılmış değer ya da dönüştürülmüş işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


[Object](../../object/) öğesini bilinmeyen bir türe dönüştürür, hem akıllı işaretçi türünü hem de kutulanmış değer durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/) öğesini dönüştürmek için hedef tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | Dönüştürülecek [Object](../../object/). |

### ReturnValue

Açılmış değer ya da dönüştürülmüş işaretçi.

## Ayrıca Bakınız

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
