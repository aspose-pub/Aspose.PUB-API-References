---
title: "System::Collections::Generic::BaseKVCollection sınıfı"
linktitle: "BaseKVCollection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::BaseKVCollection sınıfı. Anahtar veya değer koleksiyonları için ortak kodu tutar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 700
url: /tr/cpp/system.collections.generic/basekvcollection/
---
## BaseKVCollection class


Anahtarlar veya değerler koleksiyonları için ortak kodu tutar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```


| Parametre | Açıklama |
| --- | --- |
| Dict | [Dictionary](../dictionary/) türü. |
| KV | Arayüzün kullanıldığı anahtar veya değer türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Koleksiyon oluşturur. |
| [CopyTo](./copyto/)(ArrayPtr\<KV\>, int) override | Verileri mevcut dizi öğelerine kopyalar. |
| [get_Count](./get_count/)() const override | Öğe sayısını alır. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Derlemeyi etkinleştirir, ancak bu yapı veri sahiplenmediği için gerçekte bir şey yapmaz. |

## Ayrıca Bakınız

* Class [IKVCollection](../ikvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
