---
title: "System::Collections::IEnumeratorImplValueType sınıfı"
linktitle: "IEnumeratorImplValueType"
second_title: "Aspose.PUB için C++"
description: "System::Collections::IEnumeratorImplValueType sınıfı. Genel olmayan IEnumerator uygulamasını, genel Iterator IEnumeratorImplRefType üzerine oluşturan bir sarmalayıcı - C++'ta değer tipleri için sarmalayıcı."
type: docs
weight: 800
url: /tr/cpp/system.collections/ienumeratorimplvaluetype/
---
## IEnumeratorImplValueType class


Genel Iterator [IEnumeratorImplRefType](../ienumeratorimplreftype/) üzerine genel olmayan [IEnumerator](../ienumerator/) uygulamasını oluşturan sarmalayıcı - değer tipleri için sarmalayıcı.

```cpp
template<typename T>class IEnumeratorImplValueType : public System::Collections::IEnumerator
```


| Parametre | Açıklama |
| --- | --- |
| T | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Current](./get_current/)() const override | Geçerli öğeyi alır. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<T\>\>) | sarmalayıcı yapıcı |
| [MoveNext](./movenext/)() override | Enumerator'ı bir sonraki öğeye taşır. Daha önce bir öğe referans alınmamışsa, referansı mevcut ilk öğeye ayarlar. Eğer konteyner sonuna gelinmişse, hiçbir şey yapmaz. |

## Ayrıca Bakınız

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PUB for C++](../../)
