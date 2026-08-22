---
title: "System::Net::Cache::HttpRequestCacheLevel enum"
linktitle: "HttpRequestCacheLevel"
second_title: "Aspose.PUB için C++"
description: "System::Net::Cache::HttpRequestCacheLevel enum. Bu enum, C++'ta HTTP için önbellek ayarlarını tanımlar."
type: docs
weight: 400
url: /tr/cpp/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


Enum, HTTP için önbellek ayarlarını tanımlar.

```cpp
enum class HttpRequestCacheLevel
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | 0 | Bir kaynağa yönelik isteği, kaynağın önbellekteki kopyasını kullanarak ya da isteği sunucuya göndererek karşılar. |
| BypassCache | 1 | İsteği sunucuyu kullanarak karşılar. |
| CacheOnly | 2 | Her zaman bir kaynağı almak için istemci önbelleğini kullanır. |
| CacheIfAvailable | 3 | Kaynak önbellekte mevcutsa önbellekten bir kaynak isteğini karşılar, aksi takdirde sunucuya bir istek gönderir. |
| Revalidate | 4 | İstemci zaman damgası, sunucudaki kaynağın zaman damgasıyla aynıysa yerel kopya kullanılır. Aksi takdirde, bir kaynak sunucudan indirilir. |
| Reload | 5 | Bir kaynak her zaman sunucudan indirilir. |
| NoCacheNoStore | 6 | Asla önbellekten kaynak kullanarak bir isteği karşılamaz ve kaynakları önbelleğe almaz. |
| CacheOrNextCacheOnly | 7 | Bir kaynağa yönelik isteği, yerel bilgisayarın önbelleğinden ya da LAN üzerindeki uzak bir önbellekten karşılar. |
| Refresh | 8 | İsteği, sunucuyu kullanarak ya da yerel önbellek dışındaki bir önbelleği kullanarak karşılar. |

## Ayrıca Bakınız

* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
