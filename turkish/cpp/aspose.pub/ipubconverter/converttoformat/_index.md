---
title: "Aspose::Pub::IPubConverter::ConvertToFormat metodu"
linktitle: "ConvertToFormat"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::IPubConverter::ConvertToFormat metodu. PUB belgesini belirtilen formata dönüştürür ve sonucu C++'ta verilen akıma kaydeder."
type: docs
weight: 100
url: /tr/cpp/aspose.pub/ipubconverter/converttoformat/
---
## IPubConverter::ConvertToFormat(System::SharedPtr\<Document\>, System::SharedPtr\<System::IO::Stream\>, PubExportFormats) method


Belirtilen formata PUB belgesini dönüştürür ve sonucu verilen akışa kaydeder.

```cpp
virtual void Aspose::Pub::IPubConverter::ConvertToFormat(System::SharedPtr<Document> doc, System::SharedPtr<System::IO::Stream> outputStream, PubExportFormats outFormat)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| doküman | System::SharedPtr\<Document\> | PUB belgesi |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Çıktı akışı |
| outFormat | PubExportFormats | Format seçenekleri |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Enum [PubExportFormats](../../pubexportformats/)
* Class [IPubConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
## IPubConverter::ConvertToFormat(System::SharedPtr\<Document\>, System::String, PubExportFormats) method


PUB belgesini belirtilen formata dönüştürür ve sonucu *fileName* konumundaki dosyaya kaydeder.

```cpp
virtual void Aspose::Pub::IPubConverter::ConvertToFormat(System::SharedPtr<Document> doc, System::String fileName, PubExportFormats outFormat)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| doküman | System::SharedPtr\<Document\> | PUB belgesi |
| fileName | System::String | Dosyanın konumu |
| outFormat | PubExportFormats | Format seçenekleri |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Enum [PubExportFormats](../../pubexportformats/)
* Class [IPubConverter](../)
* Namespace [Aspose::Pub](../../)
* Library [Aspose.PUB for C++](../../../)
