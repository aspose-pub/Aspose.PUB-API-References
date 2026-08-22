---
title: "System::IO::DirectoryInfo::EnumerateFileSystemInfos yöntemi"
linktitle: "EnumerateFileSystemInfos"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::EnumerateFileSystemInfos yöntemi. Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri içeren yinelenebilir bir koleksiyon döndürür C++."
type: docs
weight: 700
url: /tr/cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri içeren yinelenebilir bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosya ve dizinlerin ad deseni |

### ReturnValue

Bulunan dosya ve dizinleri temsil eden ve adları **searchPattern** ile eşleşen [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçilerin yinelenebilir koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosya ve dizinlerin ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Bulunan dosya ve dizinleri temsil eden ve adları **searchPattern** ile eşleşen [FileSystemInfo](../../filesysteminfo/) nesnelerine ortak işaretçilerin yinelenebilir koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
