---
title: "System::Net::ServicePointManager Klasse"
linktitle: "ServicePointManager"
second_title: "Aspose.PUB für C++"
description: "System::Net::ServicePointManager Klasse. Verwaltet die Lebenszyklusphasen (Erstellen, Pflegen und Löschen) von ServicePoint-Klasseninstanzen. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3200
url: /de/cpp/system.net/servicepointmanager/
---
## ServicePointManager class


Verwaltet die Lebenszyklusphasen (Erstellen, Pflegen und Löschen) von [ServicePoint](../servicepoint/)-Klasseninstanzen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ServicePointManager : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [get_CertificatePolicy](./get_certificatepolicy/)() | Liefert eine Zertifikatspolicy. |
| static [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Ruft einen Wert ab, der angibt, ob das Zertifikat gegen die Sperrliste der Zertifizierungsstelle geprüft werden muss. |
| static [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Ruft die maximale Anzahl gleichzeitiger Verbindungen ab, die von den ServicePoint-class Instanzen erlaubt sind. |
| static [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Ruft einen Timeout in Millisekunden ab, während dessen eine DNS-Auflösung als gültig betrachtet wird. |
| static [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Ruft einen Wert ab, der angibt, ob eine DNS-Auflösung unter den zutreffenden IP-Adressen rotiert. |
| static [get_EncryptionPolicy](./get_encryptionpolicy/)() | Gibt die Verschlüsselungsrichtlinie zurück, die von der aktuellen Instanz verwendet wird. |
| static [get_Expect100Continue](./get_expect100continue/)() | Ruft einen Wert ab, der angibt, ob die ServicePoint-class Instanzen das 100-Continue-Verhalten verwenden. |
| static [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Ruft die maximale Leerlaufzeit der ServicePoint-class Instanzen ab. |
| static [get_MaxServicePoints](./get_maxservicepoints/)() | Ruft die maximale Anzahl der ServicePoint-class Instanzen ab, die von der aktuellen Instanz verwaltet werden können. |
| static [get_ReusePort](./get_reuseport/)() | Ruft einen Wert ab, der angibt, ob die Ausgangsverbindungssockets die Option 'SO_REUSE_UNICASTPORT' verwenden. |
| static [get_SecurityProtocol](./get_securityprotocol/)() | Ruft den Sicherheitprotokolltyp ab, der von den ServicePoint-class Instanzen verwendet wird, die von der aktuellen Instanz verwaltet werden. |
| static [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Ruft den Rückruf ab, der zur Validierung eines Serverzertifikats verwendet wird. |
| static [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Ruft einen Wert ab, der angibt, ob die ServicePoint-class Instanzen den Nagle-Algorithmus verwenden. |
| static [set_CertificatePolicy](./set_certificatepolicy/)(System::SharedPtr\<ICertificatePolicy\>) | Legt eine Zertifikatspolicy fest. |
| static [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(bool) | Legt einen Wert fest, der angibt, ob das Zertifikat gegen die Sperrliste der Zertifizierungsstelle geprüft werden muss. |
| static [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(int32_t) | Legt die maximale Anzahl gleichzeitiger Verbindungen fest, die von den ServicePoint-class Instanzen erlaubt sind. |
| static [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(int32_t) | Legt einen Timeout in Millisekunden fest, während dessen eine DNS-Auflösung als gültig betrachtet wird. |
| static [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(bool) | Legt einen Wert fest, der angibt, ob eine DNS-Auflösung unter den zutreffenden IP-Adressen rotiert. |
| static [set_Expect100Continue](./set_expect100continue/)(bool) | Legt einen Wert fest, der angibt, ob die ServicePoint-class Instanzen das 100-Continue-Verhalten verwenden. |
| static [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(int32_t) | Legt die maximale Leerlaufzeit der ServicePoint-class Instanzen fest. |
| static [set_MaxServicePoints](./set_maxservicepoints/)(int32_t) | Legt die maximale Anzahl der ServicePoint-class Instanzen fest, die von der aktuellen Instanz verwaltet werden können. |
| static [set_ReusePort](./set_reuseport/)(bool) | Legt einen Wert fest, der angibt, ob die Ausgangsverbindungssockets die Option 'SO_REUSE_UNICASTPORT' verwenden. |
| static [set_SecurityProtocol](./set_securityprotocol/)(SecurityProtocolType) | Legt den Sicherheitprotokolltyp fest, der von den ServicePoint-class Instanzen verwendet wird, die von der aktuellen Instanz verwaltet werden. |
| static [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)(Security::RemoteCertificateValidationCallback) | Legt den Rückruf fest, der zur Validierung eines Serverzertifikats verwendet wird. |
| static [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Legt einen Wert fest, der angibt, ob die ServicePoint-class Instanzen den Nagle-Algorithmus verwenden. |
| static [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Setzt den Wert, der angibt, ob die Option 'Keep-Alive' aktiviert ist. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | RTTI-Informationen. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | Die Standardanzahl persistenter Verbindungen. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PUB for C++](../../)
