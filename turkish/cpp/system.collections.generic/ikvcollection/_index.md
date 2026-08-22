---
title: "System::Collections::Generic::IKVCollection sınıfı"
linktitle: "IKVCollection"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Generic::IKVCollection sınıfı. Sözlük benzeri konteynerin anahtarlarını veya değerlerini içeren konteynerin arayüzü. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2500
url: /tr/cpp/system.collections.generic/ikvcollection/
---
## IKVCollection class


Sözlük benzeri konteynerin anahtarlarını veya değerlerini içeren konteynerin arayüzü. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T>class IKVCollection : public System::Collections::Generic::IList<T>
```


| Parametre | Açıklama |
| --- | --- |
| T | [KeyValuePair](../keyvaluepair/) tipi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const T\&) override | Konteynere öğe ekler. |
| [Clear](./clear/)() override | Konteynerdeki tüm öğeleri siler. |
| [Contains](./contains/)(const T\&) const override | Öğenin konteyner içinde bulunup bulunmadığını denetler. |
| virtual [get_Count](./get_count/)() const | Konteynerdeki öğe sayısını alır. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Konteynerin yalnızca okunur olup olmadığını kontrol eder. |
| virtual [GetEnumerator](./getenumerator/)() | RTTI bilgisi. |
| virtual [idx_get](./idx_get/)(int) const | Alıcı işlev. |
| [idx_set](./idx_set/)(int, T) override | Ayarlayıcı işlev. |
| [IndexOf](./indexof/)(const T\&) const override | Konteynerdeki öğenin indeksini alır. |
| [Insert](./insert/)(int, const T\&) override | Belirtilen konuma öğe ekler. |
| [Remove](./remove/)(const T\&) override | Konteynerden öğeyi kaldırır. |
| [RemoveAt](./removeat/)(int) override | Belirtilen konumdaki öğeyi kaldırır. |

## Ayrıca Bakınız

* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
