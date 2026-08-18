---
title: "System::Net::Cache::HttpCacheAgeControl enum"
linktitle: "HttpCacheAgeControl"
second_title: "Aspose.PUB für C++"
description: "System::Net::Cache::HttpCacheAgeControl enum. CacheAgeControl wird verwendet, um Präferenzen bezüglich des Alters und der Frische von zwischengespeicherten Elementen in C++ anzugeben."
type: docs
weight: 300
url: /de/cpp/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum


CacheAgeControl wird verwendet, um Präferenzen hinsichtlich des Alters und der Frische von zwischengespeicherten Elementen anzugeben.

```cpp
enum class HttpCacheAgeControl
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Nur für den internen Gebrauch. |
| MinFresh | 1 | Inhalt kann aus dem Cache entnommen werden, wenn die verbleibende Zeit bis zum Ablauf größer oder gleich der mit diesem Wert angegebenen Zeit ist. |
| MaxAge | 2 | Inhalt kann aus dem Cache entnommen werden, bis er älter ist als das mit diesem Wert angegebene Alter. |
| MaxStale | 4 | Inhalt kann aus dem Cache entnommen werden, nachdem er abgelaufen ist, bis die mit diesem Wert angegebene Zeit verstrichen ist. |
| MaxAgeAndMinFresh | 3 | MaxAge und MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge und MaxStale. |

## Siehe auch

* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
