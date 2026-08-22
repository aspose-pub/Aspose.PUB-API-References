---
title: "System::IO::DirectoryInfo::GetDirectories yöntemi"
linktitle: "GetDirectories"
second_title: "Aspose.PUB için C++"
description: "System::IO::DirectoryInfo::GetDirectories yöntemi. C++'ta mevcut nesne tarafından temsil edilen dizinde bulunan tüm alt dizinleri temsil eden DirectoryInfo nesnelerine ortak işaretçiler içeren bir dizi döndürür."
type: docs
weight: 1200
url: /tr/cpp/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method


Mevcut nesne tarafından temsil edilen dizinde bulunan tüm alt dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçiler içeren bir dizi döndürür.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&) method


Geçerli nesne tarafından temsil edilen dizinde belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dizinlerin ad deseni |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&, SearchOption) method


Geçerli nesne tarafından temsil edilen dizinde ya da bu dizinden kök alan bütün dizin ağacında belirtilen arama kriterlerini karşılayan dizinleri arar.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| searchPattern | const String\& | Aranacak dizinlerin ad deseni |
| searchOption | SearchOption | Aramanın yalnızca geçerli nesne tarafından temsil edilen dizinde mi yoksa bu nesnenin temsil ettiği dizinin kök dizin ağacındaki tüm dizinlerde mi yapılacağını belirtir |

### ReturnValue

Bulunan ve adları **searchPattern** ile eşleşen dizinleri temsil eden [DirectoryInfo](../) nesnelerine ortak işaretçilerin bir dizisi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
