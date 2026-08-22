---
title: "System::IO::BasicSTDIStreamWrapper class"
linktitle: "BasicSTDIStreamWrapper"
second_title: "Aspose.PUB için C++"
description: "System::IO::BasicSTDIStreamWrapper sınıfı. std::basic_istream ve türevleri için System.IO.Stream benzeri bir sarmalayıcıyı temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Yığın üzerinde veya operator new kullanarak bu tipin örneği oluşturulmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 200
url: /tr/cpp/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper class


std::basic_istream ve türevleri için bir [System.IO.Stream](../stream/)-benzeri sarmalayıcıyı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Yığın üzerinde veya operator new kullanarak bu tipin örneği oluşturulmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) | Yeni bir [BasicSTDIStreamWrapper](./) örneği oluşturur. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const BasicSTDIStreamWrapper\&) | Kopya yapıcı. Silindi. |
| [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış veriyi temel depolamaya yazar. Desteklenmiyor! |
| [operator=](./operator=/)(const BasicSTDIStreamWrapper\&) | Kopya atama operatörü. Silindi. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Eğer sarmalama modu ikili ise, belirtilen sayıda baytı akıştan okur, aksi takdirde belirtilen sayıda karakteri okur ve uint8_t tipine dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Akıştan belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar. |
| [ReadByte](./readbyte/)() override | Eğer sarmalama modu ikili ise, son çözülen karakter deposundan tek bir bayt okur, aksi takdirde akıştan tek bir karakter okur ve uint8_t tipine dönüştürür. |
| [SetLength](./setlength/)(int64_t) override | Mevcut nesne tarafından temsil edilen akışın uzunluğunu ayarlar. Desteklenmiyor! |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Eğer sarmalama modu ikili ise, belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar; aksi takdirde, belirtilen bayt dizisinden belirtilen bayt alt aralığını char_type tipine dönüştürür ve ardından sonucu akışa yazar. Desteklenmiyor! |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| [WriteByte](./writebyte/)(uint8_t) override | Eğer sarmalama modu ikili ise, belirtilen 8 bitlik işaretsiz tam sayı değerini akışa yazar; aksi takdirde, onu char_type tipine dönüştürür ve ardından sonucu akışa yazar. Desteklenmiyor! |
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
