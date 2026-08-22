---
title: "System::Net::Cookie::VerifySetDefaults yöntemi"
linktitle: "VerifySetDefaults"
second_title: "Aspose.PUB için C++"
description: "System::Net::Cookie::VerifySetDefaults yöntemi. C++'da varsayılan özniteliğin değerlerini doğrular ve ayarlar."
type: docs
weight: 4200
url: /tr/cpp/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults method


Varsayılan öznitelik değerlerini doğrular ve ayarlar.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| variant | CookieVariant | Çerezin spesifikasyonu. |
| uri | System::SharedPtr\<Uri\> | İç alanları başlatmak için kullanılan Uri sınıfı örneği. |
| isLocalDomain | bool | Çerezin yerel alana itildiğini gösteren bir değer. |
| localDomain | String | Yerel bir alan adı. |
| setDefault | bool | Çerezin özniteliklerinin varsayılan değerleriyle başlatılması gerekip gerekmediğini gösteren bir değer. |
| shouldThrow | bool | Belirtilen değerler geçersiz olduğunda bir istisnanın atılıp atılmayacağını gösteren bir değer. |

### ReturnValue

Tüm değerler geçerli olduğunda doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.PUB for C++](../../../)
