---
title: "System::ComponentModel::DoWorkEventArgs sınıfı"
linktitle: "DoWorkEventArgs"
second_title: "Aspose.PUB için C++"
description: "System::ComponentModel::DoWorkEventArgs sınıfı. DoWork olay argümanları. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve C++'da fonksiyonlara argüman olarak geçirmek için bu işaretçiyi kullanın."
type: docs
weight: 600
url: /tr/cpp/system.componentmodel/doworkeventargs/
---
## DoWorkEventArgs class


DoWork olay argümanları. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class DoWorkEventArgs : public System::ComponentModel::CancelEventArgs
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [DoWorkEventArgs](./doworkeventargs/)(const SharedPtr\<System::Object\>\&) | RTTI bilgisi. |
| [get_Argument](./get_argument/)() | Argument özelliğini alır; uygulanmadı. |
| [get_Result](./get_result/)() | Result özelliğini alır; uygulanmadı. |
| [set_Result](./set_result/)(const SharedPtr\<System::Object\>\&) | Result özelliğini ayarlar; uygulanmadı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Boş bir [EventArgs](../../system/eventargs/) paylaşımlı işaretçiyi (null işaretçi) temsil eden bir statik üye. |
## Ayrıca Bakınız

* Class [CancelEventArgs](../canceleventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
