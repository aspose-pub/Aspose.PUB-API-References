---
title: "System::Web::Services::Protocols::SoapHttpClientProtocol class"
linktitle: "SoapHttpClientProtocol"
second_title: "Aspose.PUB için C++"
description: "System::Web::Services::Protocols::SoapHttpClientProtocol sınıfı. SOAP kullanıldığında istemci vekil hizmetleri bu sınıftan türemelidir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 900
url: /tr/cpp/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol class


SOAP kullanıldığında istemci vekil hizmetleri bu sınıftan türemelidir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Discover](./discover/)() | Mevcut örneği XML [Web](../../system.web/) hizmetine bağlar. |
| [get_SoapVersion](./get_soapversion/)() | SOAP sürümünü alır. |
| [InitializeSerializers](./initializeserializers/)(const System::TypeInfo\&, System::SharedPtr\<System::Xml::Serialization::XmlSerializerImplementation\>, String) | Dahili alanları başlatır. |
| [set_SoapVersion](./set_soapversion/)(SoapProtocolVersion) | SOAP sürümünü ayarlar. |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [HttpWebClientProtocol](../httpwebclientprotocol/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
