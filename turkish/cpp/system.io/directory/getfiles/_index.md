---
title: "System::IO::Directory::GetFiles metodu"
linktitle: "GetFiles"
second_title: "Aspose.PUB için C++"
description: "System::IO::Directory::GetFiles metodu. Belirtilen dizinde ya da belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları C++'da arar."
type: docs
weight: 1200
url: /tr/cpp/system.io/directory/getfiles/
---
## Directory::GetFiles method


Belirtilen dizinde ya da belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Aranacak dizine tam veya göreli yol |
| searchPattern | const String\& | Aranacak dosyaların ad deseni |
| searchOption | SearchOption | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı yapılacağını belirtir |

### ReturnValue

**searchPattern** ile eşleşen bulunan dosyaların tam yollarının bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
