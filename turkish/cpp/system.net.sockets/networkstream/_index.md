---
title: "System::Net::Sockets::NetworkStream class"
linktitle: "NetworkStream"
second_title: "Aspose.PUB için C++"
description: "System::Net::Sockets::NetworkStream class. Ağ erişimi için verilerin temel akışını sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'de fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 300
url: /tr/cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Verilerin ağ erişimi için temel akışını sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class NetworkStream : public System::IO::Stream
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Asenkron bir okuma işlemi başlatır. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Asenkron bir yazma işlemi başlatır. |
| [Close](./close/)(int) | Belirtilen sürenin dolmasının ardından geçerli örneği kapatır. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel depolamaya yazar. |
| [get_CanRead](./get_canread/)() const override | RTTI bilgisi. |
| [get_CanSeek](./get_canseek/)() const override | Akışın aramayı (seeking) destekleyip desteklemediğini belirler. |
| [get_CanTimeout](./get_cantimeout/)() const override | Geçerli akışın zaman aşımına uğrayıp uğrayamayacağını belirleyen bir değer alır. |
| [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını belirler. |
| [get_DataAvailable](./get_dataavailable/)() const | Okunabilir mevcut veri olup olmadığını gösteren bir değer döndürür. |
| [get_Length](./get_length/)() const override | Akışın uzunluğunu bayt cinsinden döndürür. |
| [get_Position](./get_position/)() const override | Akışın mevcut konumunu döndürür. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Akışın zaman aşımına uğramadan önce ne kadar süre okuma denemesi yapacağını milisaniye cinsinden belirleyen bir değer alır. |
| [get_Socket](./get_socket/)() | Temel [Socket](../socket/) nesnesini alır. |
| [get_WriteTimeout](./get_writetimeout/)() const override | Akışın zaman aşımına uğramadan önce ne kadar süre yazma denemesi yapacağını milisaniye cinsinden belirleyen bir değer alır. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Yeni bir örnek oluşturur. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Yeni bir örnek oluşturur. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Yeni bir örnek oluşturur. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Geçerli nesne tarafından temsil edilen akışın konumunu ayarlar. |
| [set_Position](./set_position/)(int64_t) override | Akışın konumunu ayarlar. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Geçerli akışın zaman aşımına uğrayıp uğrayamayacağını belirleyen bir değer ayarlar. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Akışın zaman aşımına uğramadan önce ne kadar süre okuma denemesi yapacağını milisaniye cinsinden belirleyen bir değer ayarlar. |
| [SetLength](./setlength/)(int64_t) override | Geçerli nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| virtual [~NetworkStream](./~networkstream/)() | Geçerli örneği yok eder. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Altta yatan bir depolama alanı olmayan bir akış. |
## Ayrıca Bakınız

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
