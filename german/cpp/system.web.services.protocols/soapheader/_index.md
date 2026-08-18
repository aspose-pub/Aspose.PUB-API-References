---
title: "System::Web::Services::Protocols::SoapHeader Klasse"
linktitle: "SoapHeader"
second_title: "Aspose.PUB für C++"
description: "System::Web::Services::Protocols::SoapHeader Klasse. Stellt den Inhalt des SOAP-Headers dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 600
url: /de/cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


Stellt den Inhalt des SOAP-Headers dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SoapHeader : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Actor](./get_actor/)() | Gibt die URI des SOAP-Header-Empfängers zurück, wenn SOAP-Version 1.1 verwendet wird. |
| [get_DidUnderstand](./get_didunderstand/)() | Gibt einen Wert zurück, der angibt, ob der SOAP-Header ordnungsgemäß verarbeitet wurde. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Gibt den Wert des Attributs 'mustUnderstand' zurück, wenn SOAP-Version 1.1 verwendet wird. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Gibt den Wert des Attributs 'mustUnderstand' zurück, wenn SOAP-Version 1.2 verwendet wird. |
| [get_EncodedRelay](./get_encodedrelay/)() | Gibt die Zeichenkettenrepräsentation des Attributwerts 'relay' zurück. |
| [get_MustUnderstand](./get_mustunderstand/)() | Gibt einen Wert zurück, der angibt, ob der SOAP-Header verstanden werden muss. |
| [get_Relay](./get_relay/)() | Gibt den Wert des Attributs 'relay' zurück. |
| [get_Role](./get_role/)() | Gibt die URI des SOAP-Header-Empfängers zurück, wenn SOAP-Version 1.2 verwendet wird. |
| [set_Actor](./set_actor/)(String) | Setzt die URI des SOAP-Header-Empfängers, wenn SOAP-Version 1.1 verwendet wird. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | Setzt einen Wert, der angibt, ob der SOAP-Header ordnungsgemäß verarbeitet wurde. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | Setzt den Wert des Attributs 'mustUnderstand', wenn SOAP-Version 1.1 verwendet wird. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | Setzt einen Wert des 'mustUnderstand'-Attributs, wenn die SOAP-Version 1.2 verwendet wird. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | Setzt eine Zeichenkettenrepräsentation des 'relay'-Attributwerts. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | Setzt einen Wert, der angibt, ob der SOAP-Header verstanden werden muss. |
| [set_Relay](./set_relay/)(bool) | Setzt einen Wert des 'relay'-Attributs. |
| [set_Role](./set_role/)(String) | Setzt die URI des SOAP-Header-Empfängers, wenn die SOAP-Version 1.2 verwendet wird. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Konstruiert eine neue Instanz. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
