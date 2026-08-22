---
title: "System::Threading::ManualResetEvent class"
linktitle: "ManualResetEvent"
second_title: "Aspose.PUB için C++"
description: "System::Threading::ManualResetEvent sınıfı. Otomatik olarak sıfırlanmayan, bekleyen iş parçacığını bildiren olay. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 400
url: /tr/cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


Otomatik olarak sıfırlanmayan, bekleyen iş parçacığını bildiren olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | RTTI bilgisi. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Fonksiyon tarafından döndürülecek özel değer, aksi takdirde zaman aşımı geçerse ve hiçbir şey sinyal göndermezse dizi içindeki sinyal verilen nesnenin indeksini döndürür. |
## Ayrıca Bakınız

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
