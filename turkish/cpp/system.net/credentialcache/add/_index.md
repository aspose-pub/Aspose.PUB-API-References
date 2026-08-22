---
title: "System::Net::CredentialCache::Add yöntemi"
linktitle: "Ekle"
second_title: "Aspose.PUB için C++"
description: "System::Net::CredentialCache::Add yöntemi. C++'de belirtilen ağ kimlik bilgilerini önbelleğe ekler."
type: docs
weight: 400
url: /tr/cpp/system.net/credentialcache/add/
---
## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Belirtilen ağ kimlik bilgilerini önbelleğe ekler.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ana bilgisayar | String | Kimlik bilgilerinin ilişkilendirildiği ana bilgisayar adı. |
| bağlantı noktası | int32_t | Bağlantı noktası numarası. |
| authenticationType | String | Kimlik doğrulama şeması. |
| kimlik bilgisi | System::SharedPtr\<NetworkCredential\> | Eklenecek kimlik bilgileri. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Belirtilen ağ kimlik bilgilerini önbelleğe ekler.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriPrefix | System::SharedPtr\<Uri\> | Kimlik bilgilerinin ilişkilendirildiği kaynağın URI öneki. |
| authenticationType | String | Kimlik doğrulama şeması. |
| kimlik bilgisi | System::SharedPtr\<NetworkCredential\> | Eklenecek kimlik bilgileri. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
