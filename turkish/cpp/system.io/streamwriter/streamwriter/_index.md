---
title: "System::IO::StreamWriter::StreamWriter yapıcı"
linktitle: "StreamWriter"
second_title: "Aspose.PUB için C++"
description: "System::IO::StreamWriter::StreamWriter yapıcı. C++'ta UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak belirtilen temel akışa karakter yazan bir StreamWriter nesnesi örneği oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor


UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak belirtilen temel akışa karakter yazan bir [StreamWriter](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin yazılacağı temel akış |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Belirtilen kodlamayı kullanarak ve varsayılan 1024 bayt boyutundaki bir tamponla belirtilen temel akışa karakter yazan bir [StreamWriter](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin yazılacağı temel akış |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor


Belirtilen kodlamayı ve belirtilen boyuttaki bir tamponu kullanarak belirtilen temel akışa karakter yazan bir [StreamWriter](../) nesnesi örneği oluşturur. Bir parametre, [StreamWriter](../) nesnesi yok edildiğinde temel akışın kapatılıp kapatılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin yazılacağı temel akış |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| buffer_size | int | Arabellek boyutunun bayt cinsinden minimum boyutu |
| leave_open | bool | Geçerli [StreamWriter](../) nesnesi yok edildiğinde temel akışın açık bırakılıp bırakılmayacağını belirtir |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamWriter::StreamWriter(const String\&) constructor


Belirtilen dosyaya karakter yazan, UTF-8 kodlamasını kullanan ve varsayılan 1024 bayt boyutunda bir arabellek kullanan bir [StreamWriter](../) nesnesi oluşturur.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Karakterlerin yazılacağı dosyanın yolu |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor


Belirtilen kodlamayı ve arabellek boyutunu kullanarak belirtilen dosyaya karakter yazan bir [StreamWriter](../) nesnesi oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Karakterlerin yazılacağı dosyanın yolu |
| ekle | bool | Verilerin belirtilen dosyaya eklenip eklenmeyeceğini (true) veya dosyanın üzerine yazılıp yazılmayacağını (false) belirtir. |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| buffer_size | int | Kullanılacak arabellek boyutu |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor


Belirtilen kodlamayı kullanarak ve varsayılan 1024 bayt boyutunda bir arabellek ile belirtilen dosyaya karakter yazan bir [StreamWriter](../) nesnesi oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirtir.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const String\& | Karakterlerin yazılacağı dosyanın yolu |
| ekle | bool | Verilerin belirtilen dosyaya eklenip eklenmeyeceğini (true) veya dosyanın üzerine yazılıp yazılmayacağını (false) belirtir. |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
