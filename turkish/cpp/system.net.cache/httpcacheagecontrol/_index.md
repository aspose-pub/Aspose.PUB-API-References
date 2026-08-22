---
title: "System::Net::Cache::HttpCacheAgeControl enum"
linktitle: "HttpCacheAgeControl"
second_title: "Aspose.PUB için C++"
description: "System::Net::Cache::HttpCacheAgeControl enum. CacheAgeControl, C++'ta önbelleğe alınan öğenin yaşı ve tazeliğiyle ilgili tercihleri belirtmek için kullanılır."
type: docs
weight: 300
url: /tr/cpp/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl, önbelleğe alınmış öğenin yaşı ve tazeliğiyle ilgili tercihleri belirtmek için kullanılır.

```cpp
enum class HttpCacheAgeControl
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Yalnızca dahili kullanım için. |
| MinFresh | 1 | İçerik, süresi dolmadan önce kalan süre, bu değerle belirtilen süreden büyük veya eşit olduğunda önbellekten alınabilir. |
| MaxAge | 2 | İçerik, bu değerle belirtilen yaştan daha eski olana kadar önbellekten alınabilir. |
| MaxStale | 4 | İçerik, süresi dolduktan sonra bu değerle belirtilen süre sona erene kadar önbellekten alınabilir. |
| MaxAgeAndMinFresh | 3 | MaxAge ve MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge ve MaxStale. |

## Ayrıca Bakınız

* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
