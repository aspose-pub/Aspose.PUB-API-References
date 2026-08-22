---
title: "System::Net::Cache::HttpRequestCachePolicy sınıfı"
linktitle: "HttpRequestCachePolicy"
second_title: "Aspose.PUB için C++"
description: "System::Net::Cache::HttpRequestCachePolicy sınıfı. RFC2616 HTTP önbellekleme semantiğini ifade eden HTTP önbellek politikası. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate (ayrılmalıdır). Bu tür bir örnek hiçbir zaman yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 100
url: /tr/cpp/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy class


RFC2616 HTTP önbellekleme semantiğini ifade eden HTTP önbellek politikası. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate (ayrılmalıdır). Bu tür bir örnek hiçbir zaman yığına (stack) ya da operator new ile oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_CacheSyncDate](./get_cachesyncdate/)() const | Önbellekte depolanan kaynakların yeniden doğrulanması gereken zamanı alır. |
| [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Önbellekte depolanan kaynakların yeniden doğrulanması gereken zamanı UTC formatında alır. Yalnızca dahili kullanım için. |
| [get_Level](./get_level/)() const | RTTI bilgisi. |
| [get_MaxAge](./get_maxage/)() const | Bir kaynak için izin verilen maksimum yaşı alır. |
| [get_MaxStale](./get_maxstale/)() const | Bir kaynak için izin verilen maksimum bayatlık değerini alır. |
| [get_MinFresh](./get_minfresh/)() const | Bir kaynak için izin verilen minimum yaşı alır. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpRequestCacheLevel) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan, TimeSpan) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(DateTime) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) | Yeni bir örnek oluşturur. |
| [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
## Ayrıca Bakınız

* Class [RequestCachePolicy](../requestcachepolicy/)
* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
