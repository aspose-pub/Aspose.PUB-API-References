---
title: "System::Net::WebExceptionStatus Enum"
linktitle: "WebExceptionStatus"
second_title: "Aspose.PUB für C++"
description: "System::Net::WebExceptionStatus Enum. Enumeriert die Statuscodes der WebException‑Klasse in C++."
type: docs
weight: 4900
url: /de/cpp/system.net/webexceptionstatus/
---
## WebExceptionStatus enum


Enumeriert die Statuscodes der WebException‑Klasse.

```cpp
enum class WebExceptionStatus
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Success | 0 | Keine Fehler aufgetreten. |
| NameResolutionFailure | 1 | Der Namensauflösungsdienst konnte den Hostnamen nicht auflösen. |
| ConnectFailure | 2 | Der entfernte Dienstpunkt konnte auf der Transporteebene nicht erreicht werden. |
| ReceiveFailure | 3 | Eine vollständige Antwort wird vom entfernten Server nicht empfangen. |
| Sendefehler | 4 | Eine vollständige Anforderung konnte nicht an den Remote-Server gesendet werden. |
| Pipeline-Fehler | 5 | Die Anforderung war eine pipelined-Anforderung und die Verbindung wurde geschlossen, bevor die Antwort empfangen wurde. |
| AnfrageAbgebrochen | 6 | Die Anfrage wurde abgebrochen oder ein nicht klassifizierbarer Fehler ist aufgetreten. |
| Protokollfehler | 7 | Die vom Server erhaltene Antwort war vollständig, zeigte jedoch einen protokollbezogenen Fehler an. |
| VerbindungGeschlossen | 8 | Die Verbindung wurde vorzeitig geschlossen. |
| Vertrauensfehler | 9 | Ein Serverzertifikat konnte nicht validiert werden. |
| SecureChannelFehler | 10 | Beim Aufbau einer Verbindung mit SSL ist ein Fehler aufgetreten. |
| ServerProtokollVerstoß | 11 | Die Serverantwort war keine gültige HTTP-Antwort. |
| KeepAliveFehler | 12 | Die Verbindung für eine Anfrage, die den 'Keep-Alive'-Header angibt, wurde unerwartet geschlossen. |
| Ausstehend | 13 | Eine interne asynchrone Anfrage ist ausstehend. |
| Zeitüberschreitung | 14 | Während des Zeitüberschreitungszeitraums für eine Anfrage wurde keine Antwort empfangen. |
| ProxyNamensauflösungsfehler | 15 | Der Namensauflösungsdienst konnte den Proxy-Hostnamen nicht auflösen. |
| UnbekannterFehler | 16 | Eine Ausnahme unbekannten Typs ist aufgetreten. |
| MessageLengthLimitExceeded | 17 | Eine Nachricht, die das angegebene Limit überschritten hat, wurde empfangen. |
| CacheEntryNotFound | 18 | Der angegebene Cache-Eintrag wurde nicht gefunden. |
| RequestProhibitedByCachePolicy | 19 | Die Anforderung wurde durch die Cache-Richtlinie nicht erlaubt. |
| RequestProhibitedByProxy | 20 | Diese Anforderung wurde vom Proxy nicht erlaubt. |

## Siehe auch

* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
