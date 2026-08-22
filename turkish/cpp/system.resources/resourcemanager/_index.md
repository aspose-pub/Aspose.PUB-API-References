---
title: "System::Resources::ResourceManager sınıfı"
linktitle: "ResourceManager"
second_title: "Aspose.PUB için C++"
description: "System::Resources::ResourceManager sınıfı. Kaynakları yönetmek için API sağlar. Gerçekleştirilmemiştir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 100
url: /tr/cpp/system.resources/resourcemanager/
---
## ResourceManager class


Kaynakları yönetmek için API sağlar. Gerçekleştirilmemiştir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ResourceManager : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Kaynağından nesneyi alır. İsim, GetObjectA tanımlama sorunu ile başa çıkmak için GetObject() değildir. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Kaynağından nesneyi alır. İsim, GetObjectA tanımlama sorunu ile başa çıkmak için GetObject() değildir. |
| virtual [GetString](./getstring/)(String) | Dize kaynağını alır. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Dize kaynağını alır. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.PUB for C++](../../)
