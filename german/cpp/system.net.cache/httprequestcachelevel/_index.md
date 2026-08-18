---
title: "System::Net::Cache::HttpRequestCacheLevel Enum"
linktitle: "HttpRequestCacheLevel"
second_title: "Aspose.PUB für C++"
description: "System::Net::Cache::HttpRequestCacheLevel enum. Der Enum beschreibt die Cache‑Einstellungen für HTTP in C++."
type: docs
weight: 400
url: /de/cpp/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum


Die Aufzählung beschreibt Cache-Einstellungen für HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Erfüllt eine Anforderung für eine Ressource entweder durch Verwendung der zwischengespeicherten Kopie der Ressource oder durch Senden einer Anforderung für die Ressource an den Server. |
| BypassCache | 1 | Erfüllt eine Anforderung, indem der Server verwendet wird. |
| CacheOnly | 2 | Verwendet stets den Client‑Cache, um eine Ressource zu erhalten. |
| CacheIfAvailable | 3 | Erfüllt eine Anforderung für eine Ressource aus dem Cache, wenn die Ressource verfügbar ist, andernfalls wird eine Anforderung an den Server gesendet. |
| Revalidate | 4 | Verwenden einer lokalen Kopie einer Ressource, wenn der Client‑Zeitstempel mit dem Zeitstempel der Ressource auf dem Server übereinstimmt. Andernfalls wird die Ressource von einem Server heruntergeladen. |
| Neu laden | 5 | Eine Ressource wird immer vom Server heruntergeladen. |
| NoCacheNoStore | 6 | Erfüllt niemals eine Anforderung, indem Ressourcen aus dem Cache verwendet werden, und cached Ressourcen nicht. |
| CacheOrNextCacheOnly | 7 | Erfüllt eine Anforderung für eine Ressource entweder aus dem Cache des lokalen Computers oder aus einem entfernten Cache im LAN. |
| Refresh | 8 | Erfüllt eine Anforderung, indem der Server oder ein anderer Cache als der lokale Cache verwendet wird. |

## Siehe auch

* Namespace [System::Net::Cache](../)
* Library [Aspose.PUB for C++](../../)
