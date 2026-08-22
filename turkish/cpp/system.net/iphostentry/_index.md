---
title: "System::Net::IPHostEntry sınıfı"
linktitle: "IPHostEntry"
second_title: "Aspose.PUB için C++"
description: "System::Net::IPHostEntry sınıfı. Bir internet ana bilgisayar adresi hakkında bilgi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisi içine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2600
url: /tr/cpp/system.net/iphostentry/
---
## IPHostEntry class


Bir internet ana bilgisayar adresi hakkında bilgi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class IPHostEntry : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AddressList](./get_addresslist/)() | Ana bilgisayarın IP adresi koleksiyonunu alır. |
| [get_Aliases](./get_aliases/)() | Ana bilgisayarın takma adlar koleksiyonunu alır. |
| [get_HostName](./get_hostname/)() const | RTTI bilgisi. |
| [IPHostEntry](./iphostentry/)() | Yeni bir örnek oluşturur. |
| [set_AddressList](./set_addresslist/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>) | Ana bilgisayarın IP adresi koleksiyonunu ayarlar. |
| [set_Aliases](./set_aliases/)(System::ArrayPtr\<String\>) | Ana bilgisayarın takma adlar koleksiyonunu ayarlar. |
| [set_HostName](./set_hostname/)(String) | Ana bilgisayar adını ayarlar. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
