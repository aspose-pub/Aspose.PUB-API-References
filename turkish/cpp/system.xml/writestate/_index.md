---
title: "System::Xml::WriteState enum"
linktitle: "WriteState"
second_title: "Aspose.PUB için C++"
description: "System::Xml::WriteState enum. C++'da XmlWriter'ın durumunu belirtir."
type: docs
weight: 5700
url: /tr/cpp/system.xml/writestate/
---
## WriteState enum


[XmlWriter](../xmlwriter/) durumunu belirtir.

```cpp
enum class WriteState
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Start | 0 | XmlWriter::Write metodunun henüz çağrılmadığını gösterir. |
| Prolog | 1 | Prologun yazıldığını gösterir. |
| Eleman | 2 | Bir öğenin başlangıç etiketinin yazıldığını gösterir. |
| Özellik | 3 | Bir özelliğin değerinin yazıldığını gösterir. |
| İçerik | 4 | Öğe içeriğinin yazıldığını gösterir. |
| Closed | 5 | [XmlWriter::Close](../xmlwriter/close/) metodunun çağrıldığını gösterir. |
| Error | 6 | Bir istisna atıldı ve bu, [XmlWriter](../xmlwriter/) nesnesini geçersiz bir duruma bıraktı. [XmlWriter::Close](../xmlwriter/close/) metodunu çağırarak [XmlWriter](../xmlwriter/) nesnesini [WriteState::Closed](./) durumuna getirebilirsiniz. Başka herhangi bir [XmlWriter](../xmlwriter/) metot çağrısı InvalidOperationException hatasına neden olur. |

## Ayrıca Bakınız

* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
