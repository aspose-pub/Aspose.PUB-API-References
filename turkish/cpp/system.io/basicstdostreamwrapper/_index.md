---
title: "System::IO::BasicSTDOStreamWrapper sınıfı"
linktitle: "BasicSTDOStreamWrapper"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSTDOStreamWrapper sınıfı. std::basic_ostream ve türevleri için System.IO.Stream benzeri bir sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 300
url: /tr/cpp/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper class


std::basic_ostream ve türevleri için bir [System.IO.Stream](../stream/)-benzeri sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) | [BasicSTDOStreamWrapper](./) sınıfının yeni bir örneğini oluşturur. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const BasicSTDOStreamWrapper\&) | Kopya yapıcı. Silindi. |
| [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel depolamaya yazar. |
| [operator=](./operator=/)(const BasicSTDOStreamWrapper\&) | Kopya atama operatörü. Silindi. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Eğer sarmalama modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okur ve uint8_t tipine dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar. Desteklenmiyor! |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar. |
| [ReadByte](./readbyte/)() override | Eğer sarmalama modu ikili ise, son çözülen karakter deposundan tek bir bayt okur, aksi takdirde akıştan tek bir karakter okur ve uint8_t tipine dönüştürür. Desteklenmiyor! |
| [SetLength](./setlength/)(int64_t) override | Geçerli nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Eğer sarmalama modu ikili ise, akışa belirtilen bayt dizisinden belirtilen bayt alt aralığını yazar, aksi takdirde belirtilen bayt dizisindeki belirtilen bayt alt aralığını char_type tipine dönüştürür ve ardından sonucu akışa yazar. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| [WriteByte](./writebyte/)(uint8_t) override | Eğer sarmalama modu ikili ise, akışa belirtilen işaretsiz 8-bit tamsayı değerini yazar, aksi takdirde onu char_type tipine dönüştürür ve ardından sonucu akışa yazar. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../stream/null/) | Altta yatan bir depolama alanı olmayan bir akış. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [BaseType](./basetype/) |  |
| [char_type](./char_type/) | RTTI bilgisi. |
| [ThisType](./thistype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [traits_type](./traits_type/) |  |
## Ayrıca Bakınız

* Class [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
