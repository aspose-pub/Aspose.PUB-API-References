---
title: "System::Net::PathList sınıfı"
linktitle: "PathList"
second_title: "Aspose.PUB için C++"
description: "System::Net::PathList sınıfı. **CookieCollection** sınıfı örneklerinin listesini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirin."
type: docs
weight: 3000
url: /tr/cpp/system.net/pathlist/
---
## PathList class


Represents the list of the [CookieCollection](../cookiecollection/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PathList : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Create](./create/)() | Yeni bir örnek oluşturur. |
| [get_Count](./get_count/)() const | Öğelerin sayısını döndürür. |
| [get_SyncRoot](./get_syncroot/)() const | Koleksiyonun senkronize edildiği nesneyi döndürür. |
| [GetCookiesCount](./getcookiescount/)() | Tüm koleksiyon öğelerinin çerez sayısını döndürür. |
| [GetEnumerator](./getenumerator/)() | Mevcut koleksiyon için yineleyiciyi döndürür. |
| [idx_get](./idx_get/)(String) | Belirtilen yol ile çerez koleksiyonunu alır. |
| [idx_set](./idx_set/)(String, System::SharedPtr\<CookieCollection\>) | Belirtilen yol ile çerez koleksiyonunu ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
