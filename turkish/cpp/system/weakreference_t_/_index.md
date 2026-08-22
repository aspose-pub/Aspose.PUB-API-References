---
title: "System::WeakReference< T > class"
linktitle: "WeakReference< T >"
second_title: "Aspose.PUB için C++"
description: "System::WeakReference< T > sınıfı. Bir nesneyi referans alan ancak o nesnenin C++'ta silinmesine izin veren zayıf referansı temsil eder."
type: docs
weight: 7400
url: /tr/cpp/system/weakreference_t_/
---
## WeakReference< T > class


Bir nesneyi referans alırken aynı zamanda o nesnenin silinmesine izin veren zayıf bir referansı temsil eder.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Referans alınan nesnenin türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [operator!=](./operator!=/)(std::nullptr_t) const | Referans alınan nesnenin null olmadığını kontrol eder. |
| [operator!=](./operator!=/)(const WeakReference\<T\>\&) const | Referans alınan nesneyi başka bir [WeakReference](../weakreference/) sınıfı örneğiyle karşılaştırır. |
| [operator==](./operator==/)(std::nullptr_t) const | Referans alınan nesnenin null olduğunu kontrol eder. |
| [operator==](./operator==/)(const WeakReference\<T\>\&) const | Referans alınan nesneyi başka bir [WeakReference](../weakreference/) sınıfı örneğiyle karşılaştırır. |
| [reset](./reset/)() |  |
| [SetTarget](./settarget/)(const SmartPtr\<T\>\&) | Mevcut [WeakReference](../weakreference/) nesnesi tarafından referans verilen nesneyi (hedefi) ayarlar. |
| [TryGetTarget](./trygettarget/)(const SmartPtr\<T\>\&) const | Mevcut [WeakReference](../weakreference/) nesnesi tarafından referans verilen nesneyi (hedefi) alır. |
| [WeakReference](./weakreference/)() | Varsayılan yapıcı. |
| [WeakReference](./weakreference/)(std::nullptr_t) | nullptr'tan yapıcı. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&) | Belirtilen nesneyi referans alarak [WeakReference](../weakreference/) sınıfının yeni bir örneğini başlatır. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&, bool) | Belirtilen nesneyi referans alarak [WeakReference](../weakreference/) sınıfının yeni bir örneğini başlatır. |

## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
