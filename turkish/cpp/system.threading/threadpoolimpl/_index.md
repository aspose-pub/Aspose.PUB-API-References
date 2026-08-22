---
title: "System::Threading::ThreadPoolImpl sınıfı"
linktitle: "ThreadPoolImpl"
second_title: "Aspose.PUB için C++"
description: "System::Threading::ThreadPoolImpl sınıfı. İş parçacığı havuzu iç veri. Bu, erişim fonksiyon(ları) tarafından bellek yönetimi yapılan tek örnek (singleton) bir türdür. C++'ta doğrudan onun örneklerini oluşturmayın."
type: docs
weight: 1000
url: /tr/cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Kullanılabilir iş parçacığı sayısını alır. |
| static [GetInitialized](./getinitialized/)() | Başlatma durumu tek örneğini alır. |
| [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Maksimum eşzamanlı iş parçacığı sayısını alır. |
| [GetMinThreads](./getminthreads/)(int\&, int\&) | Havuz tarafından oluşturulan minimum iş parçacığı sayısını alır. |
| [JoinAll](./joinall/)() | Tüm sahip olunan iş parçacıklarına katılır. Sonsuz bekler. |
| [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | İş öğesini kuyruğa ekler. |
| [SetMaxThreads](./setmaxthreads/)(int, int) | Havuzun sahip olduğu iş parçacığı sayısını ayarlar. |
| [SetMinThreads](./setminthreads/)(int, int) | Havuzun sahip olduğu minimum iş parçacığı sayısını ayarlar. |
| [ThreadPoolImpl](./threadpoolimpl/)() | Yapıcı. |
| [~ThreadPoolImpl](./~threadpoolimpl/)() | Yıkıcı. İş parçacıkları henüz sonlandırılmadıysa hepsine katılır. |
## Ayrıca Bakınız

* Namespace [System::Threading](../)
* Library [Aspose.PUB for C++](../../)
