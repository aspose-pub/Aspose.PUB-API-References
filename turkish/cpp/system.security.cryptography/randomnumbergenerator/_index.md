---
title: "System::Security::Cryptography::RandomNumberGenerator sınıfı"
linktitle: "RandomNumberGenerator"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RandomNumberGenerator sınıfı. Rastgele sayı üreteçlerinin kalıtım alması için soyut sınıf. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 2600
url: /tr/cpp/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator class


Rastgele sayı üreteçlerinin kalıtım alması için soyut sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Create](./create/)() | Rastgele veri üretmek için kullanılabilecek bir kriptografik rastgele sayı üreteci varsayılan uygulamasının bir örneğini oluşturur. Henüz uygulanmadı. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) | Mevcut dizi öğelerini rastgele baytlarla doldurur. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>, int, int) | Mevcut dizi dilimini rastgele baytlarla doldurur. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) | Mevcut dizi görünümü öğelerini rastgele baytlarla doldurur. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>, int, int) | Mevcut dizi görünümü dilimini rastgele baytlarla doldurur. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Mevcut yığın dizisi öğelerini rastgele baytlarla doldurur. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&, int, int) | Mevcut yığın dizisi dilimini rastgele baytlarla doldurur. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) | Mevcut dizi öğelerini rastgele sıfır olmayan baytlarla doldurur. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) | Mevcut dizi görünümü öğelerini rastgele sıfır olmayan baytlarla doldurur. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Mevcut yığın dizisi öğelerini rastgele sıfır olmayan baytlarla doldurur. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
