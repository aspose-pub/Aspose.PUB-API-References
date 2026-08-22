---
title: "System::IO::Directory::EnumerateDirectories metodu"
linktitle: "EnumerateDirectories"
second_title: "Aspose.PUB için C++"
description: "System::IO::Directory::EnumerateDirectories metodu. Belirtilen dizinde ya da belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri C++'da arar."
type: docs
weight: 300
url: /tr/cpp/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories method


Belirtilen dizinde ya da belirtilen dizinde köklenen tüm dizin ağacında, belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Aranacak dizine tam veya göreli yol |
| searchPattern | const String\& | Aranacak dizinlerin ad deseni |
| searchOption | SearchOption | Aramanın yalnızca belirtilen dizinde mi yoksa belirtilen dizinde köklenen tüm dizin ağacında mı yapılacağını belirtir |

### ReturnValue

**searchPattern** ile eşleşen bulunan dizinlerin tam yollarının enumerasyon koleksiyonu

## Ayrıca Bakınız

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
