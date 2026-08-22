---
title: "System::IO::FileInfo sınıfı"
linktitle: "FileInfo"
second_title: "Aspose.PUB için C++"
description: "System::IO::FileInfo sınıfı. Bir dosyanın yolunu ve bu yol tarafından işaret edilen dosyayı temsil eder ve onu manipüle etmek için yöntemler sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1400
url: /tr/cpp/system.io/fileinfo/
---
## FileInfo class


Bir dosyanın yolunu ve bu yol tarafından işaret edilen dosyayı temsil eder ve onu manipüle etmek için yöntemler sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AppendText](./appendtext/)() | Geçerli nesne tarafından temsil edilen bir dosyayı, UTF-8 kodlamasıyla metin yazmak için, 'Append' modunda ve paylaşım olmadan açar. |
| [CopyTo](./copyto/)(const String\&) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten mevcutsa, kopyalama başarısız olur. |
| [CopyTo](./copyto/)(const String\&, bool) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma kopyalar. Bir parametre, mevcut hedef dosyanın üzerine yazılıp yazılmayacağını belirtir. |
| [Create](./create/)() | Geçerli nesne tarafından temsil edilen yolun belirttiği konumda bir dosya oluşturur ve onu okuma‑yazma için, truncate modunda ve paylaşım olmadan açar. |
| [CreateText](./createtext/)() | Geçerli nesne tarafından temsil edilen yolun belirttiği konumda bir dosya oluşturur ve onu UTF-8 kodlamasıyla metin yazmak için, paylaşım olmadan açar. |
| [Decrypt](./decrypt/)() | UYGULANMADI. |
| [Delete](./delete/)() override | Geçerli nesne tarafından temsil edilen dosyayı kaldırır. |
| [Encrypt](./encrypt/)() | UYGULANMADI. |
| [FileInfo](./fileinfo/)(const String\&) | Belirtilen dosyayı temsil eden yeni bir [FileInfo](./) sınıfı örneği oluşturur. |
| [get_Directory](./get_directory/)() | Geçerli nesne tarafından temsil edilen dosyanın bulunduğu dizini temsil eden bir [DirectoryInfo](../directoryinfo/) nesnesi döndürür. |
| [get_DirectoryName](./get_directoryname/)() | Geçerli nesne tarafından temsil edilen dosyanın bulunduğu dizinin tam adını döndürür. |
| [get_Exists](./get_exists/)() override | Dosyanın mevcut olup olmadığını gösteren bir değer döndürür. |
| [get_IsReadOnly](./get_isreadonly/)() | ReadOnly özelliğinin ayarlı olup olmadığını gösteren bir değer döndürür. |
| [get_Length](./get_length/)() | Dosyanın bayt cinsinden boyutunu döndürür. |
| [get_Name](./get_name/)() override | Dosyanın adını döndürür. |
| [MoveTo](./moveto/)(const String\&) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen konuma taşır. |
| [Open](./open/)(FileMode) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda, okuma‑yazma için ve paylaşım olmadan açar. |
| [Open](./open/)(FileMode, FileAccess) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim türüyle ve paylaşım olmadan açar. |
| [Open](./open/)(FileMode, FileAccess, FileShare) | Geçerli nesne tarafından temsil edilen dosyayı belirtilen modda, belirtilen erişim türüyle ve paylaşım seçeneğiyle açar. |
| [OpenRead](./openread/)() | Geçerli nesne tarafından temsil edilen bir dosyayı yalnızca okuma için, 'Open' modunda ve okuma için paylaşımlı erişimle açar. |
| [OpenText](./opentext/)() | Geçerli nesne tarafından temsil edilen yolun belirttiği konumdaki mevcut dosyayı, UTF-8 kodlamasıyla metin okumak için ve paylaşım olmadan açar. |
| [OpenWrite](./openwrite/)() | Geçerli nesne tarafından temsil edilen bir dosyayı yalnızca yazma için, 'OpenOrCreate' modunda ve paylaşım olmadan açar. |
| [Replace](./replace/)(const String\&, const String\&) | Belirtilen hedef dosyanın içeriğini, geçerli [FileInfo](./) nesnesi tarafından temsil edilen dosya ile değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| [Replace](./replace/)(const String\&, const String\&, bool) | Belirtilen hedef dosyanın içeriğini, geçerli [FileInfo](./) nesnesi tarafından temsil edilen dosya ile değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| [set_IsReadOnly](./set_isreadonly/)(bool) | Dosyada ReadOnly özelliğini ayarlar veya kaldırır. |
| [ToString](./tostring/)() const override | Geçerli nesne tarafından temsil edilen bir yolu döndürür. |
## Ayrıca Bakınız

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
