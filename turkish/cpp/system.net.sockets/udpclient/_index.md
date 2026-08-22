---
title: "System::Net::Sockets::UdpClient sınıfı"
linktitle: "UdpClient"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::UdpClient sınıfı. Kullanıcı Datagram Protokolü (UDP) ağ hizmetleri sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta işlevlere argüman olarak geçirin."
type: docs
weight: 700
url: /tr/cpp/system.net.sockets/udpclient/
---
## UdpClient class


Kullanıcı Datagram Protokolü (UDP) ağ hizmetleri sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları oluşur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class UdpClient : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Close](./close/)() | UDP bağlantısını kapatır. |
| [Connect](./connect/)(String, int32_t) | Belirtilen ana bilgisayardaki belirtilen bağlantı noktasına bir bağlantı kurar. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Belirtilen bağlantı noktasındaki belirtilen adresteki ana bilgisayara bir bağlantı kurar. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Uzak bir uç noktaya bağlantı kurar. |
| [Dispose](./dispose/)() override | Yönetilen ve yönetilmeyen, [UdpClient](./) tarafından kullanılan kaynakları serbest bırakır. |
| [get_Client](./get_client/)() | RTTI bilgisi. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Sunucu tarafından gönderilen bir datagramı döndürür. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Uzak uç noktadaki ana bilgisayara bir UDP datagramı gönderir. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Belirtilen uzak ana bilgisayardaki belirtilen bağlantı noktasına bir UDP datagramı gönderir. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Uzak bir ana bilgisayara bir UDP datagramı gönderir. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Altta yatan ağ soketini sağlamak için kullanılır. |
| [UdpClient](./udpclient/)() | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
| [UdpClient](./udpclient/)(AddressFamily) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
| [UdpClient](./udpclient/)(int32_t) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | [UdpClient](./) sınıfının yeni bir örneğini başlatır. param local EP UDP bağlantısını bağladığınız yerel uç nokta. |
| [UdpClient](./udpclient/)(String, int32_t) | [UdpClient](./) sınıfının yeni bir örneğini oluşturur ve belirtilen bağlantı noktasındaki belirtilen uzak ana bilgisayara bağlanır. |
## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
