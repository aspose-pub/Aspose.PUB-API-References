---
title: "Typedef System::SmartPtr::ValueType"
linktitle: "ValueType"
second_title: "Aspose.PUB für C++"
description: "Typedef System::SmartPtr::ValueType. Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von System::Array in C++ ist."
type: docs
weight: 4100
url: /de/cpp/system/smartptr/valuetype/
---
## ValueType typedef


Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von [System::Array](../../array/) ist.

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Siehe auch

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
