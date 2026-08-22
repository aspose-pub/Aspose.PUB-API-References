---
title: "System::IO::DirectoryInfo::GetFileSystemInfos yöntemi"
linktitle: "GetFileSystemInfos"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::GetFileSystemInfos yöntemi. Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri temsil eden FileSystemInfo nesnelerine ait paylaşımlı işaretçileri içeren bir dizi döndürür C++'ta."
type: docs
weight: 1400
url: /tr/cpp/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() method


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ait paylaşımlı işaretçileri içeren bir dizi döndürür.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosya ve dizinlerin ad deseni |

### ReturnValue

Adları **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ait paylaşımlı işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dosya ve dizinleri arar.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosya ve dizinlerin ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Adları **searchPattern** ile eşleşen bulunan dosya ve dizinleri temsil eden [FileSystemInfo](../../filesysteminfo/) nesnelerine ait paylaşımlı işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
