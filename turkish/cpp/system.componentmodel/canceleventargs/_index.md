---
title: "System::ComponentModel::CancelEventArgs sınıfı"
linktitle: "CancelEventArgs"
second_title: "Aspose.PUB için C++"
description: "System::ComponentModel::CancelEventArgs sınıfı. İptal edilebilir olayın argümanları. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirin."
type: docs
weight: 300
url: /tr/cpp/system.componentmodel/canceleventargs/
---
## CancelEventArgs class


İptal edilebilir olayın argümanları. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class CancelEventArgs : public System::EventArgs
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CancelEventArgs](./canceleventargs/)(bool) | RTTI bilgisi. |
| [CancelEventArgs](./canceleventargs/)() | Yapıcı; Cancel özelliğini false olarak ayarlar. |
| [get_Cancel](./get_cancel/)() | Olayın iptal edilip edilmeyeceğini gösteren değeri alır. |
| [set_Cancel](./set_cancel/)(bool) | Olayın iptal edilip edilmediğini gösteren değeri ayarlar. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Boş bir [EventArgs](../../system/eventargs/) paylaşımlı işaretçiyi (null işaretçi) temsil eden bir statik üye. |
## Ayrıca Bakınız

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PUB for C++](../../)
