---
title: "System::BoxedEnum class"
linktitle: "BoxedEnum"
second_title: "Aspose.PUB için C++"
description: "System::BoxedEnum sınıfı. Kutulanmış enum değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 700
url: /tr/cpp/system/boxedenum/
---
## BoxedEnum class


Kutulanmış enum değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```


| Parametre | Açıklama |
| --- | --- |
| E | Enum değerinin türü |
| UT | Enum **E**'nin temel türü |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BoxedEnum](./boxedenum/)(E) | Belirtilen enum değerini temsil eden bir örnek oluşturur. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Kutulanmış enum sabitinin değerini 64-bit tam sayı değerine dönüştürür. |
| [IsBoxedEnum](./isboxedenum/)() override | Geçerli nesnenin enum tipinde kutulanmış bir değer temsil edip etmediğini belirler. |
| [ToString](./tostring/)() const override | Geçerli nesne tarafından temsil edilen kutulanmış değeri stringe dönüştürür. |

## Ayrıca Bakınız

* Class [BoxedValue](../boxedvalue/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
