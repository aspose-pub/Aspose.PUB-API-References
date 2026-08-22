---
title: "System::ComponentModel::RunWorkerCompletedEventArgs sınıfı"
linktitle: "RunWorkerCompletedEventArgs"
second_title: "Aspose.PUB için C++"
description: "System::ComponentModel::RunWorkerCompletedEventArgs sınıfı. Bu sınıfın bir örneği RunWorkerCompletedEventHandler temsilcisine argüman olarak geçirilir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirin."
type: docs
weight: 1300
url: /tr/cpp/system.componentmodel/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs class


Bu sınıfın bir örneği RunWorkerCompletedEventHandler temsilcisine argüman olarak geçirilir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class RunWorkerCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Result](./get_result/)() const | Asenkron bir işlemin sonucunu temsil eden değeri alır. |
| [RunWorkerCompletedEventArgs](./runworkercompletedeventargs/)(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) | RTTI bilgisi. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Boş bir [EventArgs](../../system/eventargs/) paylaşımlı işaretçiyi (null işaretçi) temsil eden bir statik üye. |
## Ayrıca Bakınız

* Class [AsyncCompletedEventArgs](../asynccompletedeventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
