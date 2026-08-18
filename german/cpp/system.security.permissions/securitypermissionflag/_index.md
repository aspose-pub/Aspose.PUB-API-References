---
title: "Enum System::Security::Permissions::SecurityPermissionFlag"
linktitle: "SecurityPermissionFlag"
second_title: "Aspose.PUB für C++"
description: "System::Security::Permissions::SecurityPermissionFlag-Enum. Flags der Sicherheitsberechtigung in C++."
type: docs
weight: 300
url: /de/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Flags der Sicherheitsberechtigung.

```cpp
enum class SecurityPermissionFlag
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoFlags | 0 | Kein Zugriff. |
| Assertion | 1 | Stelle sicher, dass die Berechtigung erteilt ist. |
| UnmanagedCode | 2 | Rufe nicht verwalteten Code auf. |
| SkipVerification | 4 | Überspringe die Code-Überprüfung. |
| Execution | 8 | Führe Code aus. |
| ControlThread | 16 | Führe Vorgänge auf Threads aus. |
| ControlEvidence | 32 | Steuere oder ändere CLR-Evidence. |
| ControlPolicy | 64 | Anzeigen und ändern der Richtlinie. |
| SerializationFormatter | 128 | Serialisieren. |
| ControlDomainPolicy | 256 | Setze Domänenrichtlinie. |
| ControlPrincipal | 512 | Steuere das Principal-Objekt. |
| ControlAppDomain | 1024 | Steuere die Anwendungsdomäne. |
| RemotingConfiguration | 2048 | Remoting konfigurieren. |
| Infrastruktur | 4096 | In die CLR-Infrastruktur einbinden. |
| BindingRedirects | 8192 | Explizite Binding-Umleitung durchführen. |
| AllFlags | 16383 | Uneingeschränkt. |

## Siehe auch

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PUB for C++](../../)
