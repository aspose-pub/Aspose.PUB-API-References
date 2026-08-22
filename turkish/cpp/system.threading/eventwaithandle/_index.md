---
title: "System::Threading::EventWaitHandle sınıfı"
linktitle: "EventWaitHandle"
second_title: "Aspose.PUB için C++"
description: "System::Threading::EventWaitHandle sınıfı. Bekleyen iş parçacığına gönderilebilen bir olay. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 200
url: /tr/cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


Bekleyen iş parçacığına gönderilebilen bir olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | RTTI bilgisi. |
| virtual [Reset](./reset/)() | Olayı sinyal vermeyen duruma ayarlar. |
| virtual [Set](./set/)() | Olayı sinyal veren duruma ayarlar. |
| [~EventWaitHandle](./~eventwaithandle/)() | Yıkıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Fonksiyon tarafından döndürülecek özel değer, aksi takdirde zaman aşımı geçerse ve hiçbir şey sinyal göndermezse dizi içindeki sinyal verilen nesnenin indeksini döndürür. |
## Ayrıca Bakınız

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
