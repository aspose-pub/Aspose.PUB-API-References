---
title: "System::Reflection::BindingFlags enum"
linktitle: "BindingFlags"
second_title: "Aspose.PUB için C++"
description: "System::Reflection::BindingFlags enum. C++'da üyeleri ve tipleri arama modlarını ve bağlamaları tanımlar."
type: docs
weight: 1100
url: /tr/cpp/system.reflection/bindingflags/
---
## BindingFlags enum


Üyeleri ve tipleri arama modlarını ve bağlamalarını tanımlar.

```cpp
enum class BindingFlags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Özel seçenek yok. |
| IgnoreCase | 1 | Öğe aranırken adın büyük/küçük harf duyarlılığını yoksay. |
| DeclaredOnly | 2 | Yalnızca tipte bildirilen üyeleri ve temel tiplerdeki olmayanları ara. |
| Instance | 4 | Örnek üyeler arasında bak. |
| Static | 8 | Statik üyeler arasında bak. |
| Public | 16 | Public üyeler arasında bak. |
| NonPublic | 32 | Non-public üyeler arasında bak. |
| FlattenHierarchy | 64 | Temel tipin public ve korumalı statik üyeleri arasında bak. |
| InvokeMethod | 256 | Yöntemi çağırır. |
| CreateInstance | 512 | Yansıtılan tipin bir örneğini oluşturur. |
| GetField | 1024 | Alan değerini alır. |
| SetField | 2048 | Alan değerini ayarlar. |
| GetProperty | 4096 | Özellik değerini alır. |
| SetProperty | 8192 | Özellik değerini ayarlar. |
| PutDispProperty | 16384 | COM özelliğini koyar. |
| PutRefDispProperty | 32768 | COM referans özelliğini koyar. |
| ExactBinding | 65536 | Tür bağlaması kesin olmalı, hiçbir tür değişikliği olmadan. |
| SuppressChangeType | 131072 | Desteklenmiyor. |
| OptionalParamBinding | 262144 | Argüman sayısına göre aşırı yüklemeyi seçer. |
| IgnoreReturn | 16777216 | COM etkileşim dönüş değerini yok sayar. |

## Ayrıca Bakınız

* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
