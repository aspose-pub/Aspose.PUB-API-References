---
title: "System::Net::Cache::RequestCacheLevel enum"
linktitle: "RequestCacheLevel"
second_title: "Aspose.PUB için C++"
description: "System::Net::Cache::RequestCacheLevel enum. Bu enum, C++'ta herhangi bir WebRequest için uygulanabilir önbellek ayarlarını açıklar."
type: docs
weight: 500
url: /tr/cpp/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


Bu enum, herhangi bir [WebRequest](../../system.net/webrequest/) için uygulanabilir önbellek ayarlarını açıklar.

```cpp
enum class RequestCacheLevel
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Bir kaynağa yönelik isteği, kaynağın önbellekteki kopyasını kullanarak ya da isteği sunucuya göndererek karşılar. |
| BypassCache | 1 | İsteği sunucuyu kullanarak karşılar. Önbellekten hiçbir giriş alınmaz. |
| CacheOnly | 2 | Yalnızca önbellekten bir kaynak isteğini karşılar. Bir kaynak istemci önbelleğinde bulunmadığında WebException fırlatılacaktır. |
| CacheIfAvailable | 3 | Kaynak önbellekte mevcutsa önbellekten bir kaynak isteğini karşılar, aksi takdirde sunucuya bir istek gönderir. |
| Revalidate | 4 | İstemci zaman damgası, sunucudaki kaynağın zaman damgasıyla aynıysa yerel kopya kullanılır. Aksi takdirde, bir kaynak sunucudan indirilir. |
| Reload | 5 | Bir kaynak her zaman sunucudan indirilir. |
| NoCacheNoStore | 6 | Asla önbellekten kaynak kullanarak bir isteği karşılamaz ve kaynakları önbelleğe almaz. |

## Ayrıca Bakınız

* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
