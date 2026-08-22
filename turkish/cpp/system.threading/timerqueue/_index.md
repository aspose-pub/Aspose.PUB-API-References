---
title: "System::Threading::TimerQueue sınıfı"
linktitle: "TimerQueue"
second_title: "Aspose.PUB için C++"
description: "System::Threading::TimerQueue sınıfı. Timer nesnelerini yöneten kuyruk. Bu sadece bir uygulamadır. Timer nesneleri kendileri oraya kaydolur, onları kullanmak için bunu yapmanıza gerek yoktur – bunun yerine Timer sınıfı API'sini kullanın. Bu, erişim işlev(ler)i tarafından bellek yönetimi yapılan bir tek örnek (singleton) türdür. C++'ta doğrudan örneklerini asla oluşturmayın."
type: docs
weight: 1200
url: /tr/cpp/system.threading/timerqueue/
---
## TimerQueue class


Kuyruğu, [Timer](../timer/) nesnelerini yöneten. Bu sadece bir uygulamadır. [Timer](../timer/) nesneleri kendileri oraya kaydolur, onları kullanmak için bunu yapmanıza gerek yoktur – bunun yerine [Timer](../timer/) sınıfı API'sini kullanın. Bu, erişim işlev(ler)i tarafından bellek yönetimi yapılan bir tek örnek (singleton) türdür. Doğrudan örneklerini asla oluşturmayın.

```cpp
class TimerQueue
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(Timer *) | Zamanlayıcıyı kuyruğa kaydeder. |
| [Delete](./delete/)(Timer *) | Zamanlayıcıyı kuyruktan siler. |
| static [GetInstance](./getinstance/)() | Uygulama tek örnek (singleton). |
| static [JoinWorkerThread](./joinworkerthread/)() | İşçi thread'ine katılır. Gerekirse sonsuz bekler. |
| [operator=](./operator=/)(const TimerQueue\&) | Kopyalama yok. |
| [TimerQueue](./timerqueue/)(const TimerQueue\&) | Kopyalama yok. |
## Ayrıca Bakınız

* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
