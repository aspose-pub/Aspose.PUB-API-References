---
title: "System::IO::Path sınıfı"
linktitle: "Yol"
second_title: "Aspose.PUB için C++"
description: "System::IO::Path sınıfı. Yolları yönetmek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. C++'ta hiçbir şekilde onun örneklerini oluşturmayın."
type: docs
weight: 1900
url: /tr/cpp/system.io/path/
---
## Path class


Yolları manipüle etmek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onun örneklerini hiçbir şekilde oluşturmamalısınız.

```cpp
class Path
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Belirtilen dosya yolundaki uzantıyı değiştirir. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Belirtilen yolun geçerli olup olmadığını, geçersiz karakterler içerip içermediğini kontrol ederek belirler. Yol geçersiz karakterler içeriyorsa bir istisna fırlatılır. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Gerekirse segmentler arasına dizin ayırıcı karakterleri ekleyerek belirtilen yol bölümlerini tek bir yolda birleştirir. |
| static [Combine](./combine/)(const String\&, const String\&) | Gerekirse segmentler arasına dizin ayırıcı karakter ekleyerek iki belirtilen yol segmentini tek bir yolda birleştirir. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Gerekirse segmentler arasına dizin ayırıcı karakterler ekleyerek üç belirtilen yol segmentini tek bir yolda birleştirir. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Gerekirse segmentler arasına dizin ayırıcı karakterler ekleyerek dört belirtilen yol segmentini tek bir yolda birleştirir. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Belirtilen yolun işaret ettiği dizinin adını döndürür. |
| static [GetExtension](./getextension/)(const String\&) | Belirtilen yolun işaret ettiği dosyanın uzantısını döndürür. |
| static [GetFileName](./getfilename/)(const String\&) | Belirtilen yolun işaret ettiği dosyanın adını döndürür. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Belirtilen yolun işaret ettiği dosyanın uzantısız adını döndürür. |
| static [GetFullPath](./getfullpath/)(const String\&) | Belirtilen yolu mutlak yola dönüştürür. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Dosya adlarında izin verilmeyen karakterleri içeren bir dizi döndürür. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Yol adlarında izin verilmeyen karakterleri içeren bir dizi döndürür. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Belirtilen yolun kök dizinini döndürür. |
| static [GetRandomFileName](./getrandomfilename/)() | Rastgele oluşturulmuş bir dosya adı döndürür. |
| static [GetTempFileName_](./gettempfilename_/)() | Benzersiz bir ada sahip yeni bir dosya oluşturur ve ona tam bir yol döndürür. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Benzersiz bir ada sahip yeni bir dosya oluşturur ve ona tam bir yol döndürür. [GetTempFileName_()](./gettempfilename_/) metodunun bir eş anlamlısıdır. |
| static [GetTempPath](./gettemppath/)() | Geçerli kullanıcının geçici dizininin yolunu döndürür. |
| static [HasExtension](./hasextension/)(const String\&) | Belirtilen yolun uzantılı bir dosyaya işaret edip etmediğini belirler. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Belirtilen yolun bir kök içerip içermediğini belirler. |
| static [NormalizePath](./normalizepath/)(const String\&) | Belirtilen yolu normalleştirir. |
| static [ToBoost](./toboost/)(const String\&) | Belirtilen yolu temsil eden boost::filesystem::path sınıfının bir örneğini döndürür. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Belirtilen Boost'un path nesnesinin dize temsilini döndürür. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Bir yoldaki dizin seviyelerini ayırmak için kullanılan alternatif bir karakter. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Bir yoldaki dizin seviyelerini ayırmak için kullanılan bir karakter. |
| static [PathSeparator](./pathseparator/) | Ortam değişkenlerinde yol dizelerini ayırmak için kullanılan bir ayırıcı karakter. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Bir birim ayırıcı karakter. |
## Açıklamalar



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Rastgele bir dosya adı oluştur.
  auto filename = Path::GetRandomFileName();

  // Dosya adıyla ilgili bilgileri yazdır.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## Ayrıca Bakınız

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
