---
title: "System::Web::Services::Protocols::SoapHeader class"
linktitle: "SoapHeader"
second_title: "Aspose.PUB için C++"
description: "System::Web::Services::Protocols::SoapHeader sınıfı. SOAP başlığının içeriğini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 600
url: /tr/cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


SOAP başlığının içeriğini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile asla oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class SoapHeader : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Actor](./get_actor/)() | SOAP sürüm 1.1 kullanıldığında SOAP başlığı alıcısının URI'sını alır. |
| [get_DidUnderstand](./get_didunderstand/)() | SOAP başlığının doğru işlenip işlenmediğini gösteren bir değer alır. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | SOAP sürüm 1.1 kullanıldığında 'mustUnderstand' özniteliğinin değerini alır. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | SOAP sürüm 1.2 kullanıldığında 'mustUnderstand' özniteliğinin değerini alır. |
| [get_EncodedRelay](./get_encodedrelay/)() | 'relay' özniteliği değerinin dize temsili alınır. |
| [get_MustUnderstand](./get_mustunderstand/)() | SOAP başlığının anlaşılması gerekip gerekmediğini gösteren bir değer alır. |
| [get_Relay](./get_relay/)() | 'relay' özniteliğinin değerini alır. |
| [get_Role](./get_role/)() | SOAP sürüm 1.2 kullanıldığında SOAP başlığı alıcısının URI'sını alır. |
| [set_Actor](./set_actor/)(String) | SOAP sürüm 1.1 kullanıldığında SOAP başlığı alıcısının URI'sını ayarlar. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | SOAP başlığının doğru işlenip işlenmediğini gösteren bir değeri ayarlar. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | SOAP sürüm 1.1 kullanıldığında 'mustUnderstand' özniteliğinin değerini ayarlar. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | SOAP sürüm 1.2 kullanıldığında 'mustUnderstand' özniteliğinin değerini ayarlar. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | 'relay' özniteliğinin değerinin dize temsili ayarlanır. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | SOAP başlığının anlaşılması gerekip gerekmediğini gösteren bir değer ayarlar. |
| [set_Relay](./set_relay/)(bool) | 'relay' özniteliğinin değerini ayarlar. |
| [set_Role](./set_role/)(String) | SOAP sürüm 1.2 kullanıldığında SOAP başlığı alıcısının URI'sını ayarlar. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
