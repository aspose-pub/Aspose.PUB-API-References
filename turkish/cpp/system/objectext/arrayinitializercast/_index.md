---
title: "System::ObjectExt::ArrayInitializerCast yöntemi"
linktitle: "ArrayInitializerCast"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::ArrayInitializerCast yöntemi. Dizi temel değerlerini C++'ta dönüştürür (C# bunu örtülü olarak yapar ancak C++ görünüşe göre yapmaz)."
type: docs
weight: 100
url: /tr/cpp/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast method


Dizi temel değerlerini dönüştürür (C# bunu otomatik yapar ancak C++ muhtemelen yapmaz).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


| Parametre | Açıklama |
| --- | --- |
| To | Hedef tip. |
| From | Kaynak türler. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | Kaynak ... | Hedef diziye dönüştürülüp itilecek değerler. |

### ReturnValue

[Array](../../array/) containing converted copies of all arguments in the same order.

## Ayrıca Bakınız

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
