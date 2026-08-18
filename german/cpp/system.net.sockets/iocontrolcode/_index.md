---
title: "System::Net::Sockets::IOControlCode Aufzählung"
linktitle: "IOControlCode"
second_title: "Aspose.PUB für C++"
description: "System::Net::Sockets::IOControlCode-Enum. Enumeriert die IO-Steuerungscodes in C++."
type: docs
weight: 900
url: /de/cpp/system.net.sockets/iocontrolcode/
---
## IOControlCode enum


Enumeriert die [IO](../../system.io/) Steuerungscodes.

```cpp
enum class IOControlCode : int64_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AsyncIO | -2147195267 | Aktivieren oder deaktivieren Sie den asynchronen I/O‑Modus des Sockets. |
| NonBlockingIO | -2147195266 | Markieren Sie den Socket als nicht blockierend. |
| DataToRead | 1074030207 | Gibt die Anzahl der zum Lesen verfügbaren Bytes zurück. |
| OobDataRead | 1074033415 | Gibt Informationen über Out-of-Band-Daten zurück, die empfangen werden sollen. |
| AssociateHandle | -2013265919 | Verknüpfen Sie diesen Socket mit dem angegebenen Handle einer Begleit‑Schnittstelle. |
| EnableCircularQueuing | 671088642 | Ersetzt das älteste in der Warteschlange befindliche Datagramm durch ein eingehendes, wenn die eingehenden Nachrichtenwarteschlangen voll sind. |
| Flush | 671088644 | Verwirft den aktuellen Inhalt der Sendewarteschlange, die mit diesem Socket verknüpft ist. |
| GetBroadcastAddress | 1207959557 | Gibt eine SOCKADDR-Struktur zurück, die die Broadcast-Adresse für die Adressfamilie des aktuellen Sockets enthält. |
| GetExtensionFunctionPointer | -939524090 | Ruft einen Zeiger auf die angegebene Erweiterungsfunktion ab, die vom zugehörigen Dienstanbieter unterstützt wird. |
| GetQos | -939524089 | Ruft die mit dem Socket verbundene QOS-Struktur ab. |
| GetGroupQos | -939524088 | Gibt die QOS-Attribute für die Socket-Gruppe zurück. |
| MultipointLoopback | -2013265911 | Steuert, ob Daten, die von einer Anwendung auf dem lokalen Computer (nicht unbedingt vom selben Socket) in einer Multicast‑Sitzung gesendet werden, von einem Socket empfangen werden, das der Multicast‑Zielgruppe auf der Loopback‑Schnittstelle beigetreten ist. |
| MulticastScope | -2013265910 | Steuert die Anzahl der Weiterleitungen eines Multicast‑Pakets durch einen Router, auch bekannt als TTL oder Hop‑Count. |
| SetQos | -2013265909 | Setzt die QOS-Attribute für den Socket. |
| SetGroupQos | -2013265908 | Setzt die QOS-Attribute für die Socket-Gruppe. |
| TranslateHandle | -939524083 | Gibt ein Handle für den Socket zurück, das im Kontext einer Begleitschnittstelle gültig ist. |
| RoutingInterfaceQuery | -939524076 | Gibt die Schnittstellenadressen zurück, die verwendet werden können, um eine Verbindung zur angegebenen Remote-Adresse herzustellen. |
| RoutingInterfaceChange | -2013265899 | Aktiviert das Empfangen einer Benachrichtigung, wenn sich die lokale Schnittstelle, die zum Zugriff auf einen Remote-Endpunkt verwendet wird, ändert. |
| AddressListQuery | 1207959574 | Gibt die Liste der lokalen Schnittstellen zurück, an die der Socket gebunden werden kann. |
| AddressListChange | 671088663 | Aktiviert das Empfangen einer Benachrichtigung, wenn sich die Liste der lokalen Schnittstellen für die Protokollfamilie des Sockets ändert. |
| QueryTargetPnpHandle | 1207959576 | Ruft das SOCKET-Handle des zugrunde liegenden Anbieters ab. |
| NamespaceChange | -2013265895 | Steuert, ob der Socket eine Benachrichtigung erhält, wenn eine Namespace‑Abfrage ungültig wird. |
| AddressListSort | -939524071 | Sortiert eine Liste von IPv6- und IPv4-Zieladressen, um die beste verfügbare Adresse für die Herstellung einer Verbindung zu bestimmen. |
| ReceiveAll | -1744830463 | Aktiviert das Empfangen aller IPv4-Pakete im Netzwerk. |
| ReceiveAllMulticast | -1744830462 | Aktivieren Sie das Empfangen aller Multicast-IPv4-Pakete im Netzwerk. |
| ReceiveAllIgmpMulticast | -1744830461 | Aktivieren Sie das Empfangen aller IGMP-Pakete im Netzwerk. |
| KeepAliveValues | -1744830460 | Steuern Sie das Senden von TCP-Keep-Alive-Paketen und das Intervall, in dem sie gesendet werden. |
| AbsorbRouterAlert | -1744830459 | Dieser Wert entspricht der Winsock‑2-Konstanten 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Legen Sie die Schnittstelle fest, die für ausgehende Unicast-Pakete verwendet wird. |
| LimitBroadcasts | -1744830457 | Dieser Wert entspricht der Winsock‑2-Konstanten 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Binden Sie den Socket an einen angegebenen Schnittstellenindex. |
| MulticastInterface | -1744830455 | Legen Sie die Schnittstelle fest, die für ausgehende Multicast-Pakete verwendet wird. |
| AddMulticastGroupOnInterface | -1744830454 | Treten Sie einer Multicast-Gruppe über eine Schnittstelle bei, die durch ihren Index identifiziert wird. |
| DeleteMulticastGroupFromInterface | -1744830453 | Entfernen Sie den Socket aus einer Multicast-Gruppe. |

## Siehe auch

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
