---
title: "System::IO::StreamReader class"
linktitle: "StreamReader"
second_title: "Aspose.PUB için C++"
description: "System::IO::StreamReader sınıfı. Bayt akışından karakter okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Yığını (stack) üzerinde veya operator new kullanarak bu tipin örneğini asla oluşturmamalısınız, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2200
url: /tr/cpp/system.io/streamreader/
---
## StreamReader class


Bayt akışından karakter okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Yığını (stack) üzerinde veya operator new kullanarak bu tipin örneğini asla oluşturmamalısınız, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class StreamReader : public System::IO::TextReader
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Close](./close/)() override | Mevcut ve alt akışları kapatır. |
| [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| [get_BaseStream](./get_basestream/)() const | Temel akışı temsil eden bir nesneye ortak işaretçi döndürür. |
| [get_CurrentEncoding](./get_currentencoding/)() | Şu anda kullanılan kodlamayı döndürür. |
| [get_EndOfStream](./get_endofstream/)() | Akışın sonuna ulaşılıp ulaşılmadığını gösteren bir değer döndürür. |
| [Peek](./peek/)() override | Akışın okuma imlecini değiştirmeden akıştan tek bir karakter okur. |
| [Read](./read/)() override | Akıştan tek bir karakter okur. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Belirtilen akıştan belirtilen sayıda karakteri okur, bunları UTF-16 kodlamasına dönüştürür ve ortaya çıkan UTF-16 karakterlerini belirtilen konumdan başlayarak belirtilen karakter dizisine yazar. |
| [ReadLine](./readline/)() override | Akıştan karakterleri, geçerli satırın sonuna kadar okur. |
| [ReadToEnd](./readtoend/)() override | Akıştan karakterleri, akışın sonuna kadar okur. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakterleri okur. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, bool) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakterleri okur. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan belirtilen kodlamayı ve belirtilen boyuttaki bir tamponu kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [StreamReader](./streamreader/)(const System::String\&) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen dosyadan UTF-8 kodlaması ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakterleri okur. |
| [StreamReader](./streamreader/)(const System::String\&, bool) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen dosyadan UTF-8 kodlaması ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen dosyadan belirtilen kodlamayı ve varsayılan 4096 bayt boyutundaki bir tamponu kullanarak karakterleri okur. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 4096 bayt boyutundaki bir tamponu kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool, int) | [StreamReader](./) nesnesinin bir örneğini oluşturur; bu nesne, belirtilen dosyadan belirtilen kodlamayı ve belirtilen boyuttaki bir tamponu kullanarak karakterleri okur. Bir parametre, bayt sırası işareti algılamasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| [~StreamReader](./~streamreader/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
