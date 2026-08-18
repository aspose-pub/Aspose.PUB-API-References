---
title: "System::Web::Services::Protocols::SoapHeaderAttribute Klasse"
linktitle: "SoapHeaderAttribute"
second_title: "Aspose.PUB für C++"
description: "System::Web::Services::Protocols::SoapHeaderAttribute Klasse. Gibt den SOAP-Header an, den die XML-Webservice‑Methode oder der XML-Webservice‑Client verarbeiten kann. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 700
url: /de/cpp/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute class


Gibt den SOAP-Header an, den die XML [Web](../../system.web/) Service-Methode oder der XML [Web](../../system.web/) Service-Client verarbeiten kann. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Direction](./get_direction/)() | RTTI-Informationen. |
| [get_MemberName](./get_membername/)() | Ermittelt den Namen einer Member-Variablen des XML SOAP-Dienstes, die zum Empfangen des SOAP-Header-Inhalts verwendet wird. |
| [get_Required](./get_required/)() | Ermittelt einen Wert, der angibt, ob der SOAP-Header vom empfangenden XML [Web](../../system.web/) Service oder XML [Web](../../system.web/) Client verstanden und verarbeitet werden muss. |
| [set_Direction](./set_direction/)(SoapHeaderDirection) | Legt die Richtung des SOAP-Headers fest. |
| [set_MemberName](./set_membername/)(String) | Legt den Namen einer Member-Variablen des XML SOAP-Dienstes fest, die zum Empfangen des SOAP-Header-Inhalts verwendet wird. |
| [set_Required](./set_required/)(bool) | Legt einen Wert fest, der angibt, ob der SOAP-Header vom empfangenden XML [Web](../../system.web/) Service oder XML [Web](../../system.web/) Client verstanden und verarbeitet werden muss. |
| [SoapHeaderAttribute](./soapheaderattribute/)(String) | Konstruiert eine neue Instanz. |
## Siehe auch

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
