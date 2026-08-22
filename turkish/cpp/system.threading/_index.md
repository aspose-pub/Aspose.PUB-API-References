---
title: "System::Threading ad alanı"
linktitle: "System::Threading"
second_title: "Aspose.PUB için C++"
description: "C++'ta System::Threading ad alanı nasıl kullanılır."
type: docs
weight: 4900
url: /tr/cpp/system.threading/
---



## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Otomatik olarak sıfırlanan, bekleyen iş parçacığını bilgilendiren bir olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [EventWaitHandle](./eventwaithandle/) | Bekleyen iş parçacığına gönderilebilen bir olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Interlocked](./interlocked/) | İş parçacığı güvenli işlemler için API sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onun hiçbir şekilde örneklerini oluşturmamalısınız. |
| [ManualResetEvent](./manualresetevent/) | Otomatik olarak sıfırlamayan, bekleyen iş parçacığını bilgilendiren bir olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Monitor](./monitor/) | Sınıf [Monitor](./monitor/) nesnelere erişimi senkronize eden bir mekanizma sağlar. |
| [Mutex](./mutex/) | [Mutex](./mutex/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Thread](./thread/) | [Thread](./thread/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) havuz API'si, işleri kuyruğa iterek çalışan işçi thread havuzu tarafından okunmasını sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onun örneklerini hiçbir şekilde oluşturmamalısınız. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) havuz iç verileri. Bu, bellek yönetimi erişim işlev(ler)i tarafından yapılan tekil (singleton) bir türdür. Onun örneklerini doğrudan oluşturmayın. |
| [Timer](./timer/) | [Timer](./timer/) sınıfı, gecikmeden sonra işi ayrı bir thread'de yürütür. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [TimerQueue](./timerqueue/) | [Timer](./timer/) nesnelerini yöneten kuyruk. Bu sadece bir uygulamadır. [Timer](./timer/) nesneleri kendileri burada kaydolur, onları kullanmak için bunu yapmanıza gerek yok – bunun yerine [Timer](./timer/) sınıfı API'sını kullanın. Bu, bellek yönetimi erişim işlev(ler)i tarafından yapılan tekil bir türdür. Onun örneklerini doğrudan oluşturmayın. |
| [WaitHandle](./waithandle/) | Bekleme ilkel temel sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
## Enums

| Enum | Açıklama |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Thread'in apartment durumunu ayarlar. |
| [EventResetMode](./eventresetmode/) | Olay durumunun nasıl sıfırlandığını gösterir. |
| [ThreadState](./threadstate/) | Thread'in durumu. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) tek parametreli fonksiyon. |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ThreadStart](./threadstart/) | [Thread](./thread/) parametresiz fonksiyon. |
| [TimerCallback](./timercallback/) | Zamanlayıcı tarafından çağrılacak geri arama fonksiyonu. |
| [wait_handle_t](./wait_handle_t/) | Handle türü. |
| [WaitCallback](./waitcallback/) | Bir yer olduğunda yürütülecek geri arama öğesi. |
