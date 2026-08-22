---
title: "System::IO::TextWriter sınıfı"
linktitle: "TextWriter"
second_title: "Aspose.PUB için C++"
description: "System::IO::TextWriter sınıfı. Farklı hedeflere karakter dizileri yazan yazarları temsil eden sınıflar için temel sınıf. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2700
url: /tr/cpp/system.io/textwriter/
---
## TextWriter class


Farklı hedeflere karakter dizileri yazan yazarları temsil eden sınıflar için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class TextWriter : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Close](./close/)() | Akışı kapatır ve edinilen kaynakları serbest bırakır. |
| [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual [Flush](./flush/)() | Arabellek içeriğini temel akışa boşaltır. |
| virtual [get_Encoding](./get_encoding/)() | Şu anda kullanılan kodlamayı döndürür. |
| virtual [get_FormatProvider](./get_formatprovider/)() const | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| [get_FormatProvider](./get_formatprovider/)() | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| virtual [get_NewLine](./get_newline/)() const | Bir satır sonlandırıcı dizesi döndürür. |
| [get_NewLine](./get_newline/)() | Bir satır sonlandırıcı dizesi döndürür. |
| virtual [set_NewLine](./set_newline/)(const System::String\&) | Bir satır sonlandırıcı dizesi ayarlar. |
| virtual [Write](./write/)(const SharedPtr\<Object\>\&) | Belirtilen nesnenin dize temsilini akışa yazar. |
| virtual [Write](./write/)(bool) | Belirtilen boolean değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(char_t) | Belirtilen karakteri akışa yazar. |
| virtual [Write](./write/)(Decimal) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(double) | Belirtilen çift duyarlıklı kayan nokta değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(int) | Belirtilen 32-bit tam sayı değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(int64_t) | Belirtilen 64-bit tam sayı değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(float) | Belirtilen tek duyarlıklı kayan nokta değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(const String\&) | Belirtilen dizeyi akışa yazar. |
| virtual [Write](./write/)(uint32_t) | Belirtilen işaretsiz 32-bit tam sayı değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(uint64_t) | Belirtilen işaretsiz 64-bit tam sayı değerinin dize temsilini akışa yazar. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&) | Belirtilen diziden tüm karakterleri akışa yazar. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Belirtilen karakter dizisinden belirtilen UTF-16 karakter alt aralığını akışa yazar. |
| virtual [Write](./write/)(const char_t *) | Belirtilen c-dizesini akışa yazar. |
| virtual [Write](./write/)(const TypeInfo\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini akışa yazar. |
| [Write](./write/)(const String\&, const TArgs\&...) | Belirtilen değerleri belirtilen formata göre biçimlendirerek akışa yazar. |
| virtual [WriteLine](./writeline/)() | Akışa satır sonlandırıcı karakterleri yazar. |
| virtual [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) | Belirtilen nesnenin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(bool) | Belirtilen boolean değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(char_t) | Belirtilen karakteri, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(Decimal) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(double) | Belirtilen çift hassasiyetli kayan nokta değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(int) | Belirtilen 32-bit tam sayı değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(int64_t) | Belirtilen 64-bit tam sayı değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(float) | Belirtilen tek hassasiyetli kayan nokta değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(const String\&) | Belirtilen dizeyi, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(uint32_t) | Belirtilen işaretsiz 32-bit tam sayı değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(uint64_t) | Belirtilen işaretsiz 64-bit tam sayı değerinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) | Belirtilen diziden tüm karakterleri, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) | Belirtilen karakter dizisinden UTF-16 karakterlerinin belirtilen alt aralığını, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(const char_t *) | Belirtilen C-dizesini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [WriteLine](./writeline/)(const TypeInfo\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini, ardından satır sonlandırıcı karakterleri akışa yazar. |
| [WriteLine](./writeline/)(const String\&, const TArgs\&...) | Belirtilen değerleri, belirtilen biçime göre formatlayarak, ardından satır sonlandırıcı karakterleri akışa yazar. |
| virtual [~TextWriter](./~textwriter/)() | Yıkıcı. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfa ait bir paylaşımlı göstericinin takma adıdır. |
## Ayrıca Bakınız

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
