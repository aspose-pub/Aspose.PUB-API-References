---
title: "System::IO::DirectoryInfo::EnumerateFiles method"
linktitle: "EnumerateFiles"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::EnumerateFiles method. Geçerli nesne tarafından temsil edilen dizinde C++'ta bulunan tüm dosyaları içeren yinelemeli bir koleksiyon döndürür."
type: docs
weight: 600
url: /tr/cpp/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dosyaları içeren yinelenebilir bir koleksiyon döndürür.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosyaların ad deseni |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin yinelemeli koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosyaların ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin yinelemeli koleksiyonu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
