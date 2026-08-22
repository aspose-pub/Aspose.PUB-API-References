---
title: "System::Collections::Generic::BaseEnumerator sınıfı"
linktitle: "BaseEnumerator"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::BaseEnumerator sınıfı. STL tarzı tipleri C# tarzı kullanım için sarmak amacıyla tanımlanan Enumerator. Sıralı yineleyicinin varlığı dışında konteyner yapısı hakkında hiçbir doğrulama yapmaz. begin() ve end() işlevlerini kullanır. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++ içinde fonksiyonlara argüman olarak geçirin."
type: docs
weight: 600
url: /tr/cpp/system.collections.generic/baseenumerator/
---
## BaseEnumerator class


STL tarzı tipleri C# tarzı kullanım için sarmak amacıyla tanımlanan Enumerator. Sıralı yineleyicinin varlığı dışında konteyner yapısı hakkında hiçbir doğrulama yapmaz. begin() ve end() işlevlerini kullanır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


| Parametre | Açıklama |
| --- | --- |
| Kapsayıcı | STL tarzı konteyner tipi. |
| Eleman | Öğe türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BaseEnumerator](./baseenumerator/)(const Object::ptr\&, Container\&) | Yineleyiciyi başlatır. |
| [IsValid](./isvalid/)() const | [MoveNext()](./movenext/) çağrılıp çağrılmadığını ve sonun ulaşılmadığını kontrol eder. |
| [MoveNext](./movenext/)() override | Yineleyici tarzı artış. |
| [Reset](./reset/)() override | Elemanları yeniden yinelemek için yineleyiciyi sıfırlar. |

## Ayrıca Bakınız

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
