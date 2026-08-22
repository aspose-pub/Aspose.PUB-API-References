---
title: "System::Security::Permissions::SecurityPermissionFlag enum"
linktitle: "SecurityPermissionFlag"
second_title: "Aspose.PUB için C++"
description: "System::Security::Permissions::SecurityPermissionFlag enum. C++'de güvenlik izni bayrakları."
type: docs
weight: 300
url: /tr/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Güvenlik izninin bayrakları.

```cpp
enum class SecurityPermissionFlag
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| NoFlags | 0 | Erişim yok. |
| Assertion | 1 | İznin verildiğini doğrula. |
| UnmanagedCode | 2 | Yönetilmeyen kodu çağır. |
| SkipVerification | 4 | Kod doğrulamasını atla. |
| Execution | 8 | Kodu çalıştır. |
| ControlThread | 16 | İş parçacıkları üzerinde işlemler gerçekleştir. |
| ControlEvidence | 32 | CLR kanıtını kontrol et veya değiştir. |
| ControlPolicy | 64 | Politikayı görüntüle ve değiştir. |
| SerializationFormatter | 128 | Serileştir. |
| ControlDomainPolicy | 256 | Alan politikası ayarla. |
| ControlPrincipal | 512 | Principal nesnesini kontrol et. |
| ControlAppDomain | 1024 | Uygulama alanını kontrol et. |
| RemotingConfiguration | 2048 | Uzak nesne yapılandırmasını ayarla. |
| Altyapı | 4096 | CLR altyapısına bağlan. |
| BindingRedirects | 8192 | Açık bağlama yönlendirmesini gerçekleştir. |
| AllFlags | 16383 | Sınırsız. |

## Ayrıca Bakınız

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PUB for C++](../../)
