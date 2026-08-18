---
title: "System::Web::Services::Protocols::SoapDocumentServiceAttribute class"
linktitle: "SoapDocumentServiceAttribute"
second_title: "Aspose.PUB für C++"
description: "System::Web::Services::Protocols::SoapDocumentServiceAttribute class. Legt das Standardformat für SOAP-Anfragen und -Antworten fest. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 500
url: /de/cpp/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute class


Legt das Standardformat für SOAP-Anfragen und -Antworten fest. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_ParameterStyle](./get_parameterstyle/)() | RTTI-Informationen. |
| [get_RoutingStyle](./get_routingstyle/)() | Ermittelt einen Wert, der zeigt, wie die SOAP-Nachrichten zum Dienst geroutet werden. |
| [get_Use](./get_use/)() | Liest die Parameterformatierung. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Setzt einen Wert, der angibt, ob Parameter innerhalb eines einzelnen XML-Elements unter dem 'Body'-Element gekapselt sind. |
| [set_RoutingStyle](./set_routingstyle/)(SoapServiceRoutingStyle) | Setzt einen Wert, der zeigt, wie die SOAP-Nachrichten zum Dienst geroutet werden. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Setzt die Parameterformatierung. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Konstruiert eine neue Instanz. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse) | Konstruiert eine neue Instanz. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse, SoapParameterStyle) | Konstruiert eine neue Instanz. |
## Siehe auch

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
