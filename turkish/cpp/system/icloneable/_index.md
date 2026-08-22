---
title: "System::ICloneable sınıfı"
linktitle: "ICloneable"
second_title: "Aspose.PUB için C++"
description: "System::ICloneable sınıfı. Nesne kopyalama - bir nesnenin kopyasını oluşturma yeteneği sağlayan bir yöntemi tanımlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 3200
url: /tr/cpp/system/icloneable/
---
## ICloneable class


Bir nesnenin kopyasını oluşturma - nesne kopyalama yeteneği sağlayan bir yöntemi tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ICloneable : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Clone](./clone/)() | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
