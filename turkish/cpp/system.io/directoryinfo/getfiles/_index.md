---
title: "System::IO::DirectoryInfo::GetFiles method"
linktitle: "GetFiles"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::GetFiles method. Geçerli nesne tarafından temsil edilen dizinde C++'ta bulunan tüm dizinleri temsil eden FileInfo nesnelerine ortak işaretçileri içeren bir dizi döndürür."
type: docs
weight: 1300
url: /tr/cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Geçerli nesne tarafından temsil edilen dizinde bulunan tüm dizinleri temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçileri içeren bir dizi döndürür.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosyaların ad deseni |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dosyaları arar.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dosyaların ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dosyaları temsil eden [FileInfo](../../fileinfo/) nesnelerine ortak işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
