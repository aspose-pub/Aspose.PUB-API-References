---
title: "System::IO::File::Create yöntemi"
linktitle: "Create"
second_title: "Aspose.PUB için C++"
description: "System::IO::File::Create yöntemi. Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya oluşturur (veya mevcut dosyanın üzerine yazar) ve C++'ta okuma ve yazma erişimi için açar."
type: docs
weight: 500
url: /tr/cpp/system.io/file/create/
---
## File::Create method


Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya (veya mevcut dosyanın üzerine yazar) oluşturur ve okuma‑yazma erişimi için açar.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Oluşturulacak veya üzerine yazılacak dosyanın yolu |
| bufferSize | int32_t | Dosyadan okuma ve dosyaya yazma sırasında tamponlanan bayt sayısı |
| seçenekler | FileOptions | Dosyanın nasıl oluşturulacağını veya üzerine yazılacağını belirtir |

### ReturnValue

Belirtilen dosyayla ilişkili [FileStream](../../filestream/) nesnesine bir paylaşımlı işaretçi

## Ayrıca Bakınız

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileOptions](../../fileoptions/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
