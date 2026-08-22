---
title: "System::Text::RegularExpressions::GroupCollection class"
linktitle: "GroupCollection"
second_title: "Aspose.PUB için C++"
description: "System::Text::RegularExpressions::GroupCollection sınıfı. Tek bir eşleşmedeki yakalama gruplarının listesi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 400
url: /tr/cpp/system.text.regularexpressions/groupcollection/
---
## GroupCollection class


Tek bir eşleşmedeki yakalama gruplarının listesi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class GroupCollection : public System::Collections::Generic::List<GroupPtr>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const GroupPtr\&) override | Toplamaya öğe eklemeyi devre dışı bırakır. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Toplamaya grup ekler. |
| [Clear](./clear/)() override | Toplamadan öğe düşürmeyi devre dışı bırakır. |
| [get_Item](./get_item/)(int) const | [Group](../group/) erişimci. |
| [get_Item](./get_item/)(const String\&) const | [Group](../group/) erişimci. |
| [GroupCollection](./groupcollection/)(const WeakPtr\<Match\>\&) | Yapıcı. |
| virtual [idx_get](./idx_get/)(String) const | [Group](../group/) erişimci. |
| [idx_get](./idx_get/)(int) const override | [Group](../group/) erişimci. |
| [IsReadOnly](./isreadonly/)() const | Koleksiyonu yalnızca okunur olarak işaretler. |
| [operator[]](./operator[]/)(const String\&) const | [Group](../group/) erişimci. |
| [Remove](./remove/)(const GroupPtr\&) override | Toplamadan öğe kaldırmayı devre dışı bırakır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Base](./base/) | Temel sınıf. |
## Ayrıca Bakınız

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
