---
title: "System::IO::StreamReader::StreamReader yapıcı"
linktitle: "StreamReader"
second_title: "Aspose.PUB için C++"
description: "System::IO::StreamReader::StreamReader yapıcı. Belirtilen temel akışı UTF-8 kodlamasıyla ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan bir StreamReader nesnesi örneği oluşturur C++'ta."
type: docs
weight: 100
url: /tr/cpp/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor


Belirtilen temel akışı UTF-8 kodlamasıyla ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin okunacağı temel akış |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor


Belirtilen temel akışı UTF-8 kodlamasıyla ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin okunacağı temel akış |
| detectEncodingFromByteOrderMarks | bool | Akışın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Belirtilen temel akışı belirtilen kodlamayla ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin okunacağı temel akış |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor


Belirtilen temel akışı belirtilen kodlamayla ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin okunacağı temel akış |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | bool | Akışın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor


Belirtilen temel akışı belirtilen kodlamayla ve belirtilen boyuttaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | const SharedPtr\<Stream\>\& | Karakterlerin okunacağı temel akış |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | bool | Akışın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |
| bufferSize | int | Arabellek boyutunun bayt cinsinden minimum boyutu |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const System::String\&) constructor


Belirtilen dosyayı UTF-8 kodlamasıyla ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const System::String\& | Karakterlerin okunacağı dosyanın yolu |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const System::String\&, bool) constructor


Belirtilen dosyayı UTF-8 kodlamasıyla ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const System::String\& | Karakterlerin okunacağı dosyanın yolu |
| detectEncodingFromByteOrderMarks | bool | Dosyanın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor


Belirtilen dosyayı belirtilen kodlamayla ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const System::String\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor


Belirtilen temel akışı belirtilen kodlamayla ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const System::String\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | bool | Dosyanın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor


Belirtilen dosyayı belirtilen kodlamayla ve belirtilen boyuttaki bir tampon kullanarak karakter okuyan bir [StreamReader](../) nesnesi örneği oluşturur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | const System::String\& | Karakterlerin okunacağı dosyanın yolu |
| encoding | const EncodingPtr\& | Kullanılacak kodlama |
| detectEncodingFromByteOrderMarks | bool | Dosyanın başında bayt sırası işaretlerini aramak için doğru, aksi takdirde - yanlış |
| bufferSize | int | Arabellek boyutunun bayt cinsinden minimum boyutu |

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
