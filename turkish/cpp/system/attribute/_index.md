---
title: "System::Attribute sınıfı"
linktitle: "Özellik"
second_title: "Aspose.PUB için C++"
description: "System::Attribute sınıfı. Özel öznitelikler için temel sınıf. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya operator new kullanarak bu türden bir örnek oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 400
url: /tr/cpp/system/attribute/
---
## Attribute class


Özel öznitelikler için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Yığın üzerinde veya operator new kullanarak bu türden bir örnek oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class Attribute : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&, const TypeInfo\&) | Belirtilen türe uygulanan belirtilen tipte bir özel öznitelik döndürür. |
| static [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&) | Belirtilen türe uygulanan tüm özel öznitelikleri döndürür. |
## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
