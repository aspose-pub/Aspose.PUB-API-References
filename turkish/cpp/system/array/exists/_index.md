---
title: "System::Array::Exists yöntemi"
linktitle: "Exists"
second_title: "Aspose.PUB için C++"
description: "System::Array::Exists yöntemi. Belirtilen Array nesnesinin, belirtilen koşul fonksiyonunun gereksinimlerini karşılayan bir öğe içerip içermediğini C++'da belirler."
type: docs
weight: 5000
url: /tr/cpp/system/array/exists/
---
## Array::Exists method


Belirtilen [Array](../) nesnesinin, belirtilen koşulun gereksinimlerini karşılayan bir öğe içerip içermediğini belirler.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Öğenin aranacağı dizi |
| eşleşme | std::function\<bool(T)> | Gereksinimleri tanımlayan ve bir öğenin bunları karşılayıp karşılamadığını kontrol eden fonksiyon nesnesi |

### ReturnValue

Eğer **arr** belirtilen **match** tarafından tanımlanan gereksinimleri karşılayan bir öğe içeriyorsa doğru

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
