---
title: "System::Web::Services::Protocols::SoapHeaderAttribute class"
linktitle: "SoapHeaderAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Web::Services::Protocols::SoapHeaderAttribute sınıfı. XML Web hizmeti yöntemi veya XML Web hizmeti istemcisinin işleyebileceği SOAP başlığını belirtir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 700
url: /tr/cpp/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute class


XML [Web](../../system.web/) hizmet yöntemi veya XML [Web](../../system.web/) hizmet istemcisinin işleyebileceği SOAP başlığını belirtir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Direction](./get_direction/)() | RTTI bilgisi. |
| [get_MemberName](./get_membername/)() | SOAP başlık içeriğini almak için kullanılan XML SOAP hizmetinin bir üye değişken adını alır. |
| [get_Required](./get_required/)() | SOAP başlığının alıcı XML [Web](../../system.web/) hizmeti veya XML [Web](../../system.web/) hizmet istemcisi tarafından anlaşılması ve işlenmesi gerekip gerekmediğini gösteren bir değeri alır. |
| [set_Direction](./set_direction/)(SoapHeaderDirection) | SOAP başlık yönünü ayarlar. |
| [set_MemberName](./set_membername/)(String) | SOAP başlık içeriğini almak için kullanılan XML SOAP hizmetinin bir üye değişken adını ayarlar. |
| [set_Required](./set_required/)(bool) | SOAP başlığının alıcı XML [Web](../../system.web/) hizmeti veya XML [Web](../../system.web/) hizmet istemcisi tarafından anlaşılması ve işlenmesi gerekip gerekmediğini gösteren bir değeri ayarlar. |
| [SoapHeaderAttribute](./soapheaderattribute/)(String) | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
