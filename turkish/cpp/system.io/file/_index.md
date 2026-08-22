---
title: "System::IO::File sınıfı"
linktitle: "File"
second_title: "Aspose.PUB için C++"
description: "System::IO::File sınıfı. Dosyaları işlemek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. C++'ta hiçbir şekilde örnek oluşturmamalısınız."
type: docs
weight: 1300
url: /tr/cpp/system.io/file/
---
## File class


Dosyaları manipüle etmek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onun örneklerini hiçbir şekilde oluşturmamalısınız.

```cpp
class File
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [AppendAllLines](./appendalllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Belirtilen kodlamayı kullanarak, belirtilen dizi içindeki dizeleri belirtilen dosyaya ekler; her dizeyi yeni bir satıra yazar. Belirtilen dosya yoksa oluşturulur. Tüm dizeler yazıldıktan sonra dosya kapatılır. |
| static [AppendAllText](./appendalltext/)(const String\&, const String\&, const EncodingPtr\&) | Belirtilen kodlamayı kullanarak belirtilen dizeyi belirtilen dosyaya ekler. |
| static [AppendText](./appendtext/)(const String\&) | UTF-8 kodlamasını kullanarak belirtilen dosyaya metin ekleyen bir [StreamWriter](../streamwriter/) nesnesi oluşturur. Belirtilen dosya mevcut değilse, oluşturulur. |
| static [Copy](./copy/)(const String\&, const String\&, bool) | Belirtilen dosyayı belirtilen konuma kopyalar. Hedef dosya zaten mevcutsa, bir parametre bunun üzerine yazılıp yazılmayacağını belirtir. |
| static [Create](./create/)(const String\&, int32_t, FileOptions) | Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya (veya mevcut dosyanın üzerine yazar) oluşturur ve okuma‑yazma erişimi için açar. |
| static [CreateText](./createtext/)(const String\&) | UTF-8 kodlu metin yazmak için yeni bir dosya oluşturur veya mevcut dosyayı açar. |
| static [Decrypt](./decrypt/)(const String\&) | UYGULANMADI. |
| static [Delete](./delete/)(const String\&) | Belirtilen dosya veya dizini siler. |
| static [Encrypt](./encrypt/)(const String\&) | UYGULANMADI. |
| static [Exists](./exists/)(const String\&) | Belirtilen yolun mevcut bir dosyaya işaret edip etmediğini belirler. |
| static [GetAttributes](./getattributes/)(const String\&) | Belirtilen varlığın özniteliklerini döndürür. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Belirtilen varlığın oluşturulma zamanını yerel saat olarak döndürür. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Belirtilen varlığın oluşturulma zamanını UTC saat olarak döndürür. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Belirtilen varlığın son erişim zamanını yerel saat olarak döndürür. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Belirtilen varlığın son erişim zamanını UTC saat olarak döndürür. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Belirtilen varlığın son yazma zamanını yerel saat olarak döndürür. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Belirtilen varlığın son yazma zamanını UTC saat olarak döndürür. |
| static [Move](./move/)(const String\&, const String\&) | Belirtilen dosyayı yeni konuma taşır. |
| static [Open](./open/)(const String\&, FileMode) | Belirtilen dosyayı belirtilen kipte okuma ve yazma için, paylaşım olmadan açar. |
| static [Open](./open/)(const String\&, FileMode, FileAccess, FileShare) | Belirtilen dosyayı belirtilen kipte, belirtilen erişim türü ve paylaşım seçeneğiyle açar. |
| static [OpenRead](./openread/)(const String\&) | Belirtilen dosyayı yalnızca okuma için, 'Open' kipinde ve okuma için paylaşımlı erişimle açar. |
| static [OpenText](./opentext/)(const String\&, const EncodingPtr\&) | Belirtilen mevcut dosyayı UTF-8 kodlamasını kullanarak metin okumak için, paylaşım olmadan açar. |
| static [OpenWrite](./openwrite/)(const String\&) | Belirtilen dosyayı yalnızca yazma için, 'OpenOrCreate' kipinde ve paylaşım olmadan açar. |
| static [ReadAllBytes](./readallbytes/)(const String\&) | Belirtilen ikili dosyanın içeriğini bir bayt dizisine okur. |
| static [ReadAllLines](./readalllines/)(const String\&, const EncodingPtr\&) | Belirtilen metin dosyasının içeriğini satır satır, belirtilen karakter kodlamasını kullanarak bir dizi dizeye okur. |
| static [ReadAllText](./readalltext/)(const String\&, const EncodingPtr\&) | Belirtilen metin dosyasının içeriğini belirtilen karakter kodlamasını kullanarak tek bir [String](../../system/string/) nesnesine okur. |
| static [ReadLines](./readlines/)(const String\&, const EncodingPtr\&) | Belirtilen metin dosyasının içeriğini satır satır, belirtilen karakter kodlamasını kullanarak okur ve dosyanın içeriğinin tek bir satırını temsil eden dize koleksiyonunu döndürür. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, bool) | Bir dosyanın içeriğini diğeriyle değiştirir ve değiştirilen dosyanın bir yedeğini oluşturur. |
| static [SetAttributes](./setattributes/)(const String\&, FileAttributes) | Belirtilen dosyada belirtilen öznitelikleri ayarlar. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | UYGULANMADI. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | UYGULANMADI. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | UYGULANMADI. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | UYGULANMADI. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Belirtilen varlığın son yazma zamanını yerel saat olarak ayarlar. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Belirtilen varlığın son yazma zamanını UTC saat olarak ayarlar. |
| static [WriteAllBytes](./writeallbytes/)(const String\&, const ArrayPtr\<uint8_t\>\&) | Belirtilen ikili dosyanın üzerine yazar ve belirtilen baytları ona yazar. |
| static [WriteAllLines](./writealllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Yeni bir metin dosyası oluşturur veya mevcut dosyanın üzerine yazar ve belirtilen kodlamayı kullanarak, belirtilen yinelenebilir dize koleksiyonundaki tüm dizeleri dosyaya yazar, her dize yeni bir satıra. |
| static [WriteAllLines](./writealllines/)(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) | Yeni bir metin dosyası oluşturur veya mevcut dosyanın üzerine yazar ve belirtilen kodlamayı kullanarak, belirtilen dize dizisindeki tüm dizeleri dosyaya yazar, her dize yeni bir satıra. |
| static [WriteAllText](./writealltext/)(const String\&, const String\&, const EncodingPtr\&) | Yeni bir metin dosyası oluşturur veya mevcut dosyanın üzerine yazar ve belirtilen kodlamayı kullanarak, belirtilen dizenin içeriğini dosyaya yazar. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Bir dosyadan okuma ve dosyaya yazma sırasında tamponlanan bayt sayısının varsayılan değeri. |
## Ayrıca Bakınız

* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
