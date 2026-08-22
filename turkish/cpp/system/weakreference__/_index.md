---
title: "System::WeakReference<> class"
linktitle: "WeakReference<>"
second_title: "Aspose.PUB için C++"
description: "System::WeakReference<> class. C++'de bir nesneyi referans alırken, o nesnenin silinmesine izin veren bir zayıf referansı temsil eder."
type: docs
weight: 7500
url: /tr/cpp/system/weakreference__/
---
## WeakReference<> class


Bir nesneyi referans alırken aynı zamanda o nesnenin silinmesine izin veren zayıf bir referansı temsil eder.

```cpp
class WeakReference<> : public System::WeakReference<System::Object>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsAlive](./get_isalive/)() const | Mevcut [WeakReference](../weakreference/) nesnesi tarafından referans verilen nesnenin silinip silinmediğine dair bir gösterge alır. |
| [get_Target](./get_target/)() const | Mevcut [WeakReference](../weakreference/) nesnesi tarafından referans verilen nesneyi (hedefi) alır. |
| [set_Target](./set_target/)(const SmartPtr\<Object\>\&) | Mevcut [WeakReference](../weakreference/) nesnesi tarafından referans verilen nesneyi (hedefi) ayarlar. |
| [WeakReference](./weakreference/)() | Varsayılan yapıcı. |
| [WeakReference](./weakreference/)(std::nullptr_t) | nullptr'tan yapıcı. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&) | Belirtilen nesneyi referans alarak [WeakReference](../weakreference/) sınıfının yeni bir örneğini başlatır. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&, bool) | Belirtilen nesneyi referans alarak [WeakReference](../weakreference/) sınıfının yeni bir örneğini başlatır. |
## Ayrıca Bakınız

* Class [WeakReference](../weakreference/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
