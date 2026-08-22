---
title: "System::ObjectExt::UnboxToNullable method"
linktitle: "UnboxToNullable"
second_title: "Aspose.PUB için C++"
description: "System::ObjectExt::UnboxToNullable method. Nesneyi C++'ta nullable (null değer alabilir) türe açar."
type: docs
weight: 1600
url: /tr/cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable method


Nesneyi null atanabilir tipe kutudan çıkarır.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=true)
```


| Parametre | Açıklama |
| --- | --- |
| T | Hedef tür. |

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) kutusundan çıkarmak için. |
| güvenli | bool | Doğru ise, başarısızlıkta nullptr döndür, aksi takdirde InvalidCastException fırlat. |

### ReturnValue

Açılmış nullable değer (null olabilir).

## Ayrıca Bakınız

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
