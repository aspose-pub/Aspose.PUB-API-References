---
title: "System::Net::Sockets::UdpClient Klasse"
linktitle: "UdpClient"
second_title: "Aspose.PUB für C++"
description: "System::Net::Sockets::UdpClient Klasse. Bietet Netzwerkdienste des User Datagram Protocol (UDP). Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 700
url: /de/cpp/system.net.sockets/udpclient/
---
## UdpClient class


Bietet Netzwerkdienste des User Datagram Protocol (UDP). Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class UdpClient : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Close](./close/)() | Schließt die UDP-Verbindung. |
| [Connect](./connect/)(String, int32_t) | Stellt eine Verbindung zum angegebenen Port auf dem angegebenen Host her. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Stellt eine Verbindung zum Host an der angegebenen Adresse und dem angegebenen Port her. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Stellt eine Verbindung zu einem entfernten Endpunkt her. |
| [Dispose](./dispose/)() override | Gibt die verwalteten und nicht verwalteten Ressourcen frei, die vom [UdpClient](./) verwendet werden. |
| [get_Client](./get_client/)() | RTTI-Informationen. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Gibt ein vom Server gesendetes Datagramm zurück. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Sendet ein UDP-Datagramm an den Host am entfernten Endpunkt. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Sendet ein UDP-Datagramm an den angegebenen Port des angegebenen entfernten Hosts. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Sendet ein UDP-Datagramm an einen entfernten Host. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Wird verwendet, um den zugrunde liegenden Netzwerksocket bereitzustellen. |
| [UdpClient](./udpclient/)() | Initialisiert eine neue Instanz der Klasse [UdpClient](./). |
| [UdpClient](./udpclient/)(AddressFamily) | Initialisiert eine neue Instanz der Klasse [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t) | Initialisiert eine neue Instanz der Klasse [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | Initialisiert eine neue Instanz der Klasse [UdpClient](./). |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | Initialisiert eine neue Instanz der Klasse [UdpClient](./). param local EP der lokale Endpunkt, an den Sie die UDP-Verbindung binden. |
| [UdpClient](./udpclient/)(String, int32_t) | Erstellt eine neue Instanz der Klasse [UdpClient](./) und verbindet sich mit dem angegebenen entfernten Host am angegebenen Port. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
