---
title: "System::Net::IPEndPoint sınıfı"
linktitle: "IPEndPoint"
second_title: "Aspose.PUB için C++"
description: "System::Net::IPEndPoint sınıfı. IP adresi ve bir bağlantı noktasını içeren bir ağ uç noktasını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2500
url: /tr/cpp/system.net/ipendpoint/
---
## IPEndPoint class


IP adresi ve bir bağlantı noktasını içeren bir ağ uç noktasını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class IPEndPoint : public System::Net::EndPoint
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Create](./create/)(System::SharedPtr\<SocketAddress\>) override | Belirtilen soket adresini kullanarak [EndPoint](../endpoint/) sınıfının yeni bir örneğini oluşturun. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| [get_Address](./get_address/)() | Uç nokta adresini alır. |
| [get_AddressFamily](./get_addressfamily/)() override | RTTI bilgisi. |
| [get_Port](./get_port/)() | Bağlantı noktasının numarasını alır. |
| [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini sağlar. |
| [GetImpl](./getimpl/)() const override | Uygulamaya bir işaretçi döndürür. |
| [IPEndPoint](./ipendpoint/)(int64_t, int32_t) | Yeni bir örnek oluşturur. |
| [IPEndPoint](./ipendpoint/)(System::SharedPtr\<IPAddress\>, int32_t) | Yeni bir örnek oluşturur. |
| [set_Address](./set_address/)(System::SharedPtr\<IPAddress\>) | Uç nokta adresini ayarlar. |
| [set_Port](./set_port/)(int32_t) | Bağlantı noktasının numarasını ayarlar. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Any](./any/) | Herhangi bir IPv4 adresi ve herhangi bir bağlantı noktası için uç nokta. |
| static [AnyPort](./anyport/) | Herhangi bir bağlantı noktasının kullanılabileceğini gösteren bir değer. |
| static [IPv6Any](./ipv6any/) | Herhangi bir IPv6 adresi ve herhangi bir bağlantı noktası için uç nokta. |
| static [MaxPort](./maxport/) | Maksimum bağlantı noktası numarası. |
| static [MinPort](./minport/) | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
