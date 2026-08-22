---
title: "System::Web::Services::Protocols::SoapClientMessage class"
linktitle: "SoapClientMessage"
second_title: "Aspose.PUB için C++"
description: "System::Web::Services::Protocols::SoapClientMessage class. Gönderilen bir SOAP isteğinde veya alınan bir SOAP yanıtında bulunan verileri temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman System::SmartPtr işaretçisi içine sarılmalı ve bu işaretçi C++'ta fonksiyonlara argüman olarak geçirilmelidir."
type: docs
weight: 300
url: /tr/cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Bir SOAP isteği gönderildiğinde veya bir SOAP yanıtı alındığında verileri temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarılmalı ve bu işaretçi fonksiyonlara argüman olarak geçirilmelidir.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Action](./get_action/)() override | 'SOAPAction' özniteliğinin bir değerini döndürür. |
| [get_Client](./get_client/)() | İstemci proxy sınıfının bir örneğini döndürür. |
| virtual [get_OneWay](./get_oneway/)() | İstemcinin bir yöntemin işlenmesini sunucunun bitirmesini bekleyip beklemediğini gösteren bir değeri döndürür. |
| [get_SoapVersion](./get_soapversion/)() override | Kullanılan SOAP sürümünü döndürür. |
| [get_Url](./get_url/)() override | XML [Web](../../system.web/) hizmetinin URL'sini döndürür. |
| [SoapClientMessage](./soapclientmessage/)(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
