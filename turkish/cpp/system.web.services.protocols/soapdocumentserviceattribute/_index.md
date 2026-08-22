---
title: "System::Web::Services::Protocols::SoapDocumentServiceAttribute class"
linktitle: "SoapDocumentServiceAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Web::Services::Protocols::SoapDocumentServiceAttribute class. SOAP istekleri ve yanıtları için varsayılan biçimi ayarlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman System::SmartPtr işaretçisi içine sarılmalı ve bu işaretçi C++'ta fonksiyonlara argüman olarak geçirilmelidir."
type: docs
weight: 500
url: /tr/cpp/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute class


SOAP istekleri ve yanıtları için varsayılan biçimi ayarlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıf her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine sarılmalı ve bu işaretçi fonksiyonlara argüman olarak geçirilmelidir.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_ParameterStyle](./get_parameterstyle/)() | RTTI bilgisi. |
| [get_RoutingStyle](./get_routingstyle/)() | SOAP mesajlarının hizmete nasıl yönlendirildiğini gösteren bir değeri alır. |
| [get_Use](./get_use/)() | Parametre biçimlendirmesini alır. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Parametrelerin 'Body' öğesinin altında tek bir XML öğesi içinde kapsüllenip kapsüllenmediğini gösteren bir değeri ayarlar. |
| [set_RoutingStyle](./set_routingstyle/)(SoapServiceRoutingStyle) | SOAP mesajlarının hizmete nasıl yönlendirildiğini gösteren bir değeri ayarlar. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Parametre biçimlendirmesini ayarlar. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Yeni bir örnek oluşturur. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse) | Yeni bir örnek oluşturur. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse, SoapParameterStyle) | Yeni bir örnek oluşturur. |
## Ayrıca Bakınız

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
