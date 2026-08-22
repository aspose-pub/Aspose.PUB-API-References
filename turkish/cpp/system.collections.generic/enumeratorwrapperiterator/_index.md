---
title: "System::Collections::Generic::EnumeratorWrapperIterator sınıfı"
linktitle: "EnumeratorWrapperIterator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::EnumeratorWrapperIterator sınıfı. Önceden oluşturulmuş enumerator'ı saran ve C++'ta tüm çağrıları ona yönlendiren yineleyici."
type: docs
weight: 1500
url: /tr/cpp/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator class


Önceden oluşturulmuş yineleyiciyi saran ve tüm çağrıları ona yönlendiren yineleyici.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


| Parametre | Açıklama |
| --- | --- |
| Eleman | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const SharedPtr\<IEnumerator\<Element\>\>\&) |  |
| [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri hareket ettirir. m_is_end ve m_pointer'ı güncellemelidir. |
| [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | İki yineleyicinin aynı öğeye işaret edip etmediğini kontrol eder. |
| virtual [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Yıkıcı. |

## Ayrıca Bakınız

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
