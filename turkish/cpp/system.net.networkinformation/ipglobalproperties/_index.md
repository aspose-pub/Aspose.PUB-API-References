---
title: "System::Net::NetworkInformation::IPGlobalProperties sınıfı"
linktitle: "IPGlobalProperties"
second_title: "Aspose.PUB için C++"
description: "System::Net::NetworkInformation::IPGlobalProperties sınıfı. Yerel bilgisayarın ağ bağlantısı hakkında bilgi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmaktan kaçının, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 200
url: /tr/cpp/system.net.networkinformation/ipglobalproperties/
---
## IPGlobalProperties class


Yerel bilgisayarın ağ bağlantısı hakkında bilgi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmaktan kaçının, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class IPGlobalProperties : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [get_DomainName](./get_domainname/)() | Yerel bilgisayarın kayıtlı olduğu alan adını döndürür. |
| virtual [get_HostName](./get_hostname/)() | Yerel bilgisayarın ana bilgisayar adını döndürür. |
| static [GetIPGlobalProperties](./getipglobalproperties/)() | RTTI bilgisi. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Net::NetworkInformation](../)
* Library [Aspose.PUB for C++](../../)
