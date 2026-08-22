---
title: "System::Xml::XmlTextWriter::XmlTextWriter yapıcı"
linktitle: "XmlTextWriter"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextWriter::XmlTextWriter yapıcı. Belirtilen akış ve kodlamayı kullanarak C++'ta XmlTextWriter sınıfının bir örneğini oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Belirtilen akış ve kodlamayı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | const SharedPtr\<IO::Stream\>\& | Yazmak istediğiniz akış. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Oluşturulacak kodlama. Kodlama **nullptr** ise, akışı UTF-8 olarak yazar ve **ProcessingInstruction**'dan kodlama özniteliğini atlar. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor


Belirtilen TextWriter'ı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | const SharedPtr\<IO::TextWriter\>\& | Yazmak için TextWriter. TextWriter'ın zaten doğru kodlamaya ayarlandığı varsayılır. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor


Belirtilen dosyayı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | const String\& | Yazılacak dosya adı. Dosya mevcutsa, içeriği keser ve yeni içerikle üzerine yazar. |
| encoding | const SharedPtr\<Text::Encoding\>\& | Oluşturulacak kodlama. Kodlama **nullptr** ise dosyayı UTF-8 olarak yazar ve **ProcessingInstruction** öğesinden kodlama özniteliğini atlar. |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
