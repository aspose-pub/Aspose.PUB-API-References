---
title: "System::Collections::Generic::IEqualityComparer sınıfı"
linktitle: "IEqualityComparer"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::IEqualityComparer sınıfı. İki nesneyi eşitlik açısından karşılaştırma imkanı sağlayan bir arabirim. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt üzerinde ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2400
url: /tr/cpp/system.collections.generic/iequalitycomparer/
---
## IEqualityComparer class


Eşitlik açısından iki nesneyi karşılaştırma imkanı sağlayan bir arabirim. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığıt üzerinde ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class IEqualityComparer : public virtual System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan tip. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Equals](./equals/)(T, T) const | RTTI bilgisi. |
| virtual [GetHashCode](./gethashcode/)(T) const | Bir nesne için karma kodunu alır. |

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
