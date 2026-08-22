---
title: "System::Collections::Generic::ReverseEnumerator sınıfı"
linktitle: "ReverseEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::ReverseEnumerator sınıfı. Konteyner içinde ters yönde yineleme yapan yineleyici. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 3800
url: /tr/cpp/system.collections.generic/reverseenumerator/
---
## ReverseEnumerator class


Konatainer içinde ters yönde yineleme yapan yineleyici. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename Container,typename Element>class ReverseEnumerator : public System::Collections::Generic::IEnumerator<typename Container::value_type>
```


| Parametre | Açıklama |
| --- | --- |
| Kapsayıcı | Yineleme yapılacak konteyner. |
| Eleman | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Current](./get_current/)() const override | 'current' öğesini alır. |
| [IsValid](./isvalid/)() const | [MoveNext()](./movenext/) çağrılıp çağrılmadığını ve sonun ulaşılmadığını kontrol eder. |
| [MoveNext](./movenext/)() override | Yineleyici tarzı artış. |
| [Reset](./reset/)() override | Elemanları yeniden yinelemek için yineleyiciyi sıfırlar. |
| [ReverseEnumerator](./reverseenumerator/)(const Object::ptr\&, Container\&) | Yineleyiciyi başlatır. |
| virtual [~ReverseEnumerator](./~reverseenumerator/)() | Yıkıcı. |

## Ayrıca Bakınız

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
