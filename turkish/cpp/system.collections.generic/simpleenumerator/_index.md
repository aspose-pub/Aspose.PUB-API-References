---
title: "System::Collections::Generic::SimpleEnumerator sınıfı"
linktitle: "SimpleEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::SimpleEnumerator sınıfı. rbegin() ve rend() işlevlerini kullanarak öğeleri doğrudan tutan basit kapsayıcılar için yineleyici sınıfı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 3900
url: /tr/cpp/system.collections.generic/simpleenumerator/
---
## SimpleEnumerator class


rbegin() ve rend() işlevlerini kullanarak öğeleri doğrudan tutan basit kapsayıcılar için yineleyici sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename Container,typename Element>class SimpleEnumerator : public System::Collections::Generic::BaseEnumerator<Container, typename Container::value_type>
```


| Parametre | Açıklama |
| --- | --- |
| Kapsayıcı | Üzerinde yineleme yapılacak kapsayıcı türü. |
| Eleman | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Mevcut yineleyiciyi klonlar. |
| [get_Current](./get_current/)() const override | 'current' öğesini alır. |
| [SimpleEnumerator](./simpleenumerator/)(Object::ptr, Container\&) | Basit yineleyici oluşturur. |

## Ayrıca Bakınız

* Class [BaseEnumerator](../baseenumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
