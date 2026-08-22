---
title: "System::IO::FileStream::FileStream yapıcı"
linktitle: "FileStream"
second_title: "Aspose.PUB için C++"
description: "C++'da System::IO::FileStream sınıfının FileStream yapıcısını nasıl kullanılır."
type: docs
weight: 100
url: /tr/cpp/system.io/filestream/filestream/
---
## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Ayrıca Bakınız

* Class [FileStream](../)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## FileStream::FileStream(const String\&, FileMode) constructor


[FileStream](../) sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Açılacak dosyanın yolu. |
| mod | FileMode | Dosyanın açılacağı modu belirtir. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


[FileStream](../) sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Açılacak dosyanın yolu. |
| mod | FileMode | Dosyanın açılacağı modu belirtir. |
| erişim | FileAccess | İstenen erişim türü. |
| share | FileShare | Açılmış dosyaya diğer [FileStream](../) nesnelerinin sahip olduğu erişim türü. |
| buffer_size | int32_t | Okuma ve yazma işlemleri sırasında tamponlanan bayt sayısı. |
| seçenekler | FileOptions | Ek seçenekler. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
