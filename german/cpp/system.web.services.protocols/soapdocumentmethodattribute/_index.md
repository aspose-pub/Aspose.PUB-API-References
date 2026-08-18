---
title: "System::Web::Services::Protocols::SoapDocumentMethodAttribute Klasse"
linktitle: "SoapDocumentMethodAttribute"
second_title: "Aspose.PUB für C++"
description: "System::Web::Services::Protocols::SoapDocumentMethodAttribute Klasse. Gibt an, dass alle SOAP-Nachrichten, die von der Methode übergeben oder zurückgegeben werden, das Document-Format verwenden. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute class


Gibt an, dass alle SOAP-Nachrichten, die von der Methode übergeben oder zurückgegeben werden, das Document-Format verwenden. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Action](./get_action/)() | RTTI-Informationen. |
| [get_Binding](./get_binding/)() | Ermittelt die Bindung, für die eine XML-Webservice-Methode eine Operation implementiert. |
| [get_OneWay](./get_oneway/)() | Ermittelt einen Wert, der angibt, ob ein Client nicht darauf wartet, dass ein Server die Verarbeitung einer Methode beendet. |
| [get_ParameterStyle](./get_parameterstyle/)() | Ermittelt einen Wert, der angibt, ob Parameter innerhalb eines einzelnen XML-Elements unter dem 'Body'-Element gekapselt sind. |
| [get_RequestElementName](./get_requestelementname/)() | Ermittelt den Namen des XML-Elements, das mit der SOAP-Anforderung verknüpft ist und in einer Servicebeschreibung als Operation definiert wird. |
| [get_RequestNamespace](./get_requestnamespace/)() | Ermittelt den Namespace, der mit der SOAP-Anforderung verknüpft ist. |
| [get_ResponseElementName](./get_responseelementname/)() | Ermittelt den Namen des XML-Elements, das mit der SOAP-Antwort verknüpft ist. |
| [get_ResponseNamespace](./get_responsenamespace/)() | Ermittelt den Namespace, der mit der SOAP-Antwort verknüpft ist. |
| [get_Use](./get_use/)() | Ermittelt einen Wert, der die Nachrichtenkodierungsmethode bestimmt. |
| [set_Action](./set_action/)(String) | Setzt einen Wert des 'SOAPAction'-Attributs. |
| [set_Binding](./set_binding/)(String) | Setzt die Bindung, für die eine XML-Webservice-Methode eine Operation implementiert. |
| [set_OneWay](./set_oneway/)(bool) | Setzt einen Wert, der angibt, ob der Client nicht darauf wartet, dass der Server die Verarbeitung einer Methode beendet. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Setzt einen Wert, der angibt, ob Parameter innerhalb eines einzelnen XML-Elements unter dem 'Body'-Element gekapselt sind. |
| [set_RequestElementName](./set_requestelementname/)(String) | Setzt den Namen des XML-Elements, das mit der SOAP-Anforderung verknüpft ist und in einer Servicebeschreibung als Operation definiert wird. |
| [set_RequestNamespace](./set_requestnamespace/)(String) | Setzt den Namespace, der mit der SOAP-Anforderung verknüpft ist. |
| [set_ResponseElementName](./set_responseelementname/)(String) | Setzt den Namen des XML-Elements, das mit der SOAP-Antwort verknüpft ist. |
| [set_ResponseNamespace](./set_responsenamespace/)(String) | Setzt den Namespace, der mit der SOAP-Antwort verknüpft ist. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Legt einen Wert fest, der die Nachrichtenkodierungsmethode bestimmt. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Konstruiert eine neue Instanz. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)(String) | Konstruiert eine neue Instanz. |
## Siehe auch

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PUB for C++](../../)
