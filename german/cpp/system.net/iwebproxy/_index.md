---
title: "System::Net::IWebProxy Klasse"
linktitle: "IWebProxy"
second_title: "Aspose.PUB für C++"
description: "System::Net::IWebProxy Klasse. Dieses Interface wird für die Implementierung des Proxy-Zugriffs auf die WebRequest‑Klasse verwendet. Objekte dieser Klasse sollten nur über die System::MakeObject()‑Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2700
url: /de/cpp/system.net/iwebproxy/
---
## IWebProxy class


Dieses Interface wird für die Implementierung des Proxy‑Zugriffs auf die [WebRequest](../webrequest/)‑Klasse verwendet. Objekte dieser Klasse sollten nur über die [System::MakeObject()](../../system/makeobject/)‑Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
class IWebProxy : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [get_Credentials](./get_credentials/)() | RTTI-Informationen. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Gibt die Proxy‑URI zurück. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Gibt einen Wert zurück, der angibt, ob der Proxy für den angegebenen Host nicht verwendet werden darf. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Setzt Anmeldeinformationen für die Authentifizierung am Proxy‑Server. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
