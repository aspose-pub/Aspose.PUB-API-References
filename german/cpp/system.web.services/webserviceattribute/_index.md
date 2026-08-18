---
title: "System::Web::Services::WebServiceAttribute class"
linktitle: "WebServiceAttribute"
second_title: "Aspose.PUB für C++"
description: "System::Web::Services::WebServiceAttribute class. Fügt zusätzliche Informationen zum XML-Webdienst hinzu. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.web.services/webserviceattribute/
---
## WebServiceAttribute class


Fügt zusätzliche Informationen zum XML [Web](../../system.web/) Dienst hinzu. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class WebServiceAttribute : public System::Attribute
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Description](./get_description/)() | Liefert eine Nachricht, die die XML [Web](../../system.web/) Dienstbeschreibung enthält. |
| [get_Name](./get_name/)() | Liefert den Namen des XML [Web](../../system.web/) Dienstes. |
| [get_Namespace](./get_namespace/)() | Liefert den Standard-Namespace, der für den XML [Web](../../system.web/) Dienst verwendet werden soll. |
| [set_Description](./set_description/)(String) | Setzt eine Nachricht, die die XML [Web](../../system.web/) Dienstbeschreibung enthält. |
| [set_Name](./set_name/)(String) | Setzt den Namen des XML [Web](../../system.web/) Dienstes. |
| [set_Namespace](./set_namespace/)(String) | Setzt den Standard-Namespace, der für den XML [Web](../../system.web/) Dienst verwendet werden soll. |
| [WebServiceAttribute](./webserviceattribute/)() | Konstruiert eine neue Instanz. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [DefaultNamespace](./defaultnamespace/) | RTTI-Informationen. |
## Siehe auch

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services](../)
* Library [Aspose.PUB for C++](../../)
