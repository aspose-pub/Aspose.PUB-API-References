---
title: "System::Net::Sockets::LingerOption sınıfı"
linktitle: "LingerOption"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::LingerOption sınıfı. Bir soketin Close() veya Close() yöntemlerine yapılan çağrıdan sonra bağlı kalıp kalmayacağını belirtir. Ayrıca, veri gönderimi devam ederse soketin bağlı kalacağı süreyi belirtir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirin."
type: docs
weight: 200
url: /tr/cpp/system.net.sockets/lingeroption/
---
## LingerOption class


Bir soketin Close() veya Close() yöntemlerine yapılan çağrıdan sonra bağlı kalıp kalmayacağını belirtir. Ayrıca, veri gönderimi devam ederse soketin bağlı kalacağı süreyi belirtir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class LingerOption : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Enabled](./get_enabled/)() | RTTI bilgisi. |
| [get_LingerTime](./get_lingertime/)() | Gecikme zaman aşımını saniye cinsinden alır. |
| [LingerOption](./lingeroption/)(bool, int32_t) | Yeni bir örnek oluşturur. |
| [set_Enabled](./set_enabled/)(bool) | Soketin, bekleyen tüm verileri göndermeye çalışarak kapanmayı geciktirip geciktirmeyeceğini gösteren bir değeri ayarlar. |
| [set_LingerTime](./set_lingertime/)(int32_t) | Gecikme zaman aşımını saniye cinsinden ayarlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
