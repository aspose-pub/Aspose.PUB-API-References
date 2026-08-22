---
title: "Aspose::Pub::PackageDocumentItem sınıfı"
linktitle: "PackageDocumentItem"
second_title: "Aspose.PUB için C++"
description: "Aspose::Pub::PackageDocumentItem sınıfı. Paket dönüşümlerinde kullanılmak üzere Publisher belge referansları için temel sınıftır. Dönüştürülen belgenin çıktı kaynağını belirtmek için alanlar sağlar - Disk dosyası için OutputFileName ve akış için OutputStream. Ayrıca C++'da dönüşüm ayarlarını da sağlar."
type: docs
weight: 2200
url: /tr/cpp/aspose.pub/packagedocumentitem/
---
## PackageDocumentItem class


Paket dönüşümlerinde kullanılmak üzere Publisher belge referansları için temel sınıf. Dönüştürülen belgenin çıktı kaynağını belirtmek için alanlar sağlar - disk dosyası için [OutputFileName](../) ve akış için [OutputStream](../). Ayrıca dönüşüm ayarlarını da sağlar.

```cpp
class PackageDocumentItem : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_ConversionOptions](./get_conversionoptions/)() const | Dönüşüm ayarları. |
| [get_OutputFileName](./get_outputfilename/)() const | Çıktı dosyasının adı. Tam yol gereklidir. |
| [get_OutputStream](./get_outputstream/)() const | Dönüştürme sonucunu kaydetmek için çıktı akışı. |
| [PackageDocumentItem](./packagedocumentitem/)(System::String) | Yapıcı. |
| [PackageDocumentItem](./packagedocumentitem/)(System::String, System::SharedPtr\<PubToPdfConversionOptions\>) | Yapıcı. |
| [PackageDocumentItem](./packagedocumentitem/)(System::SharedPtr\<System::IO::Stream\>) | Yapıcı. |
| [PackageDocumentItem](./packagedocumentitem/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PubToPdfConversionOptions\>) | Yapıcı. |
| [set_ConversionOptions](./set_conversionoptions/)(System::SharedPtr\<PubToPdfConversionOptions\>) | Dönüşüm ayarları. |
| [set_OutputFileName](./set_outputfilename/)(System::String) | Çıktı dosyasının adı. Tam yol gereklidir. |
| [set_OutputStream](./set_outputstream/)(System::SharedPtr\<System::IO::Stream\>) | Dönüştürme sonucunu kaydetmek için çıktı akışı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [Aspose::Pub](../)
* Library [Aspose.PUB for C++](../../)
