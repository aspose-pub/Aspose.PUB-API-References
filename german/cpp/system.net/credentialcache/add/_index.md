---
title: "System::Net::CredentialCache::Add method"
linktitle: "Addition"
second_title: "Aspose.PUB für C++"
description: "System::Net::CredentialCache::Add method. Fügt die angegebenen Netzwerk‑Anmeldeinformationen dem Cache in C++ hinzu."
type: docs
weight: 400
url: /de/cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Fügt die angegebenen Netzwerk-Anmeldedaten dem Cache hinzu.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | String | Der Hostname, mit dem die Anmeldeinformationen verknüpft sind. |
| Port | int32_t | Die Portnummer. |
| authenticationType | String | Das Authentifizierungsschema. |
| Anmeldeinformation | System::SharedPtr\<NetworkCredential\> | Die hinzuzufügenden Anmeldeinformationen. |

## Siehe auch

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Fügt die angegebenen Netzwerk-Anmeldedaten dem Cache hinzu.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | Der URI‑Präfix der Ressource, dem die Anmeldeinformationen zugeordnet sind. |
| authenticationType | String | Das Authentifizierungsschema. |
| Anmeldeinformation | System::SharedPtr\<NetworkCredential\> | Die hinzuzufügenden Anmeldeinformationen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
