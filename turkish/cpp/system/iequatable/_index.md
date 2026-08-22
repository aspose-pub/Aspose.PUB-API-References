---
title: "System::IEquatable sınıfı"
linktitle: "IEquatable"
second_title: "Aspose.PUB için C++"
description: "System::IEquatable sınıfı. İki nesnenin eşitliğini belirleyen bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya operator new kullanarak bu türden bir örnek oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 3700
url: /tr/cpp/system/iequatable/
---
## IEquatable class


İki nesnenin eşitliğini belirleyen bir yöntem tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya operator new kullanarak bu türden bir örnek oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T>class IEquatable : public virtual System::Object
```


| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan nesnelerin tipi |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Equals](./equals/)(T) | Geçerli ve belirtilen nesnelerin eşit olup olmadığını belirler. |

## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
