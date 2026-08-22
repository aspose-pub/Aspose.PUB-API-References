---
title: "System::Net::Http::Headers::ObjectCollection sınıfı"
linktitle: "ObjectCollection"
second_title: "Aspose.PUB için C++"
description: "System::Net::Http::Headers::ObjectCollection sınıfı. C++'ta nesnelerin koleksiyonunu temsil eder."
type: docs
weight: 1600
url: /tr/cpp/system.net.http.headers/objectcollection/
---
## ObjectCollection class


Nesnelerin koleksiyonunu temsil eder.

```cpp
template<typename T>class ObjectCollection : public System::Collections::ObjectModel::Collection<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | Nesne türü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ObjectCollection](./objectcollection/)() | RTTI bilgisi. |
| [ObjectCollection](./objectcollection/)(Action\<T\>) | Yeni bir örnek oluşturur. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) olarak ayarlayın. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |

## Ayrıca Bakınız

* Class [Collection](../../system.collections.objectmodel/collection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
