---
title: "System::IO::DirectoryInfo::EnumerateDirectories method"
linktitle: "EnumerateDirectories"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::EnumerateDirectories yöntemi. Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri içeren yinelenebilir bir koleksiyon döndürür C++'ta."
type: docs
weight: 500
url: /tr/cpp/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri içeren yinelenebilir bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dizinlerin ad deseni |

### ReturnValue

Bulunan dizinlerin adları **searchPattern** ile eşleşen [DirectoryInfo](../) nesnelerine ait paylaşımlı işaretçilerin yinelenebilir koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dizinlerin ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Bulunan dizinlerin adları **searchPattern** ile eşleşen [DirectoryInfo](../) nesnelerine ait paylaşımlı işaretçilerin yinelenebilir koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
