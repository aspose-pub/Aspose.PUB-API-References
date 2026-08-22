---
title: "System::Collections::IEnumeratorImplRefType sınıfı"
linktitle: "IEnumeratorImplRefType"
second_title: "Aspose.PUB için C++"
description: "System::Collections::IEnumeratorImplRefType sınıfı. Generic Iterator IEnumeratorImplRefType üzerine jenerik olmayan IEnumerator uygulaması oluşturan sarmalayıcı - C++'da referans tipleri için sarmalayıcı."
type: docs
weight: 700
url: /tr/cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Jenerik olmayan [IEnumerator](../ienumerator/) uygulamasını generic Iterator [IEnumeratorImplRefType](./) üzerine oluşturan sarmalayıcı - referans tipleri için sarmalayıcı.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Current](./get_current/)() const override | Geçerli öğeyi alır. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | sarmalayıcı yapıcı |
| [MoveNext](./movenext/)() override | Enumerator'ı bir sonraki öğeye taşır. Daha önce bir öğe referans alınmamışsa, referansı mevcut ilk öğeye ayarlar. Eğer konteyner sonuna gelinmişse, hiçbir şey yapmaz. |

## Ayrıca Bakınız

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
