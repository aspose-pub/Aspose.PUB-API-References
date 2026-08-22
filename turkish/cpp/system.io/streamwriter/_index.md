---
title: "System::IO::StreamWriter sınıfı"
linktitle: "StreamWriter"
second_title: "Aspose.PUB için C++"
description: "System::IO::StreamWriter sınıfı. Karakterleri bir bayt akışına yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2300
url: /tr/cpp/system.io/streamwriter/
---
## StreamWriter class


Bir bayt akışına karakter yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Close](./close/)() override | Akışı kapatır ve edinilen kaynakları serbest bırakır. |
| [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| [Flush](./flush/)() override | Arabellek içeriğini temel akışa boşaltır ve ardından temel akışı boşaltır. |
| [get_AutoFlush](./get_autoflush/)() const | Her [StreamWriter](./) yöntemi [StreamWriter::Write](./write/) çağrıldığında verileri temel akışa boşaltıp boşaltmayacağını gösteren bir değer döndürür. |
| [get_BaseStream](./get_basestream/)() const | Temel akışı temsil eden bir nesneye ortak işaretçi döndürür. |
| [get_Encoding](./get_encoding/)() override | Şu anda kullanılan kodlamayı döndürür. |
| [set_AutoFlush](./set_autoflush/)(bool) | Her [StreamWriter](./) yöntemi [StreamWriter::Write](./write/) çağrıldığında verileri temel akışa boşaltması gerekip gerekmediğini belirten bir değer döndürür. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&) | Belirtilen temel akışa karakterler yazan, UTF-8 kodlamasını kullanan ve varsayılan 1024 bayt boyutunda bir tamponla [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Belirtilen temel akışa karakterler yazan, belirtilen kodlamayı kullanan ve varsayılan 1024 bayt boyutunda bir tamponla [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) | Belirtilen temel akışa karakterler yazan, belirtilen kodlamayı kullanan ve belirtilen boyutta bir tamponla [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, [StreamWriter](./) nesnesi yok edildiğinde temel akışın kapatılıp kapatılmayacağını belirtir. |
| [StreamWriter](./streamwriter/)(const String\&) | Belirtilen dosyaya karakterler yazan, UTF-8 kodlamasını kullanan ve varsayılan 1024 bayt boyutunda bir tamponla [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&) | Belirtilen dosyaya karakterler yazan, belirtilen kodlamayı kullanan ve varsayılan 1024 bayt boyutunda bir tamponla [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, verinin dosyaya eklenip eklenmeyeceğini ya da dosyanın üzerine yazılıp yazılmayacağını belirtir. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&, int) | Belirtilen dosyaya karakterler yazan, belirtilen kodlamayı ve tampon boyutunu kullanan [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, verinin dosyaya eklenip eklenmeyeceğini ya da dosyanın üzerine yazılıp yazılmayacağını belirtir. |
| [Write](./write/)(char_t) override | Belirtilen karakteri akışa yazar. |
| [Write](./write/)(const String\&) override | Belirtilen dizeyi akışa yazar. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Belirtilen nesnenin dize temsilini akışa yazar. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Belirtilen diziden tüm karakterleri akışa yazar. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Belirtilen karakter dizisinden belirtilen UTF-16 karakter alt aralığını akışa yazar. |
| [Write](./write/)(const char_t *) override | Belirtilen c-dizesini akışa yazar. |
| [Write](./write/)(const System::SharedPtr\<T\>\&) | Belirtilen nesnenin dize temsilini akışa yazar. |
| [WriteLine](./writeline/)() override | Akışa satır sonlandırıcı karakterleri yazar. |
| [WriteLine](./writeline/)(const String\&) override | Belirtilen dizeyi, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Belirtilen nesnenin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Belirtilen diziden tüm karakterleri, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Belirtilen karakter dizisinden UTF-16 karakterlerinin belirtilen alt aralığını, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const char_t *) override | Belirtilen C-dizesini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const System::SharedPtr\<T\>\&) | Belirtilen nesnenin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [~StreamWriter](./~streamwriter/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
