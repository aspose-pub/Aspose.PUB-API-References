---
title: "System::Security::Cryptography::RijndaelManaged class"
linktitle: "RijndaelManaged"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RijndaelManaged sınıfı. Yönetilen Rijndael algoritması. Yalnızca None dolgu ile ECB ve CFB modlarını ve None ve Zeros dolgularıyla CBC modunu destekler. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığıt üzerinde veya new operatörüyle oluşturulursa, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirin."
type: docs
weight: 3100
url: /tr/cpp/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged class


Yönetilen [Rijndael](../rijndael/) algoritması. Yalnızca None dolgu ile ECB ve CFB modlarını ve None ve Zeros dolgularıyla CBC modunu destekler. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığıt üzerinde veya new operatörüyle oluşturulursa, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CreateDecryptor](./createdecryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Açık parametrelerle bir şifre çözücü nesnesi oluşturur. |
| virtual [CreateDecryptor](./createdecryptor/)() | Algoritma nesnesi tarafından tanımlanan parametrelerle bir şifre çözücü nesnesi oluşturur. |
| [CreateEncryptor](./createencryptor/)(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) override | Açık parametrelerle bir şifreleyici nesnesi oluşturur. |
| virtual [CreateEncryptor](./createencryptor/)() | Algoritma nesnesi tarafından tanımlanan parametrelerle bir şifreleyici nesnesi oluşturur. |
| [GenerateIV](./generateiv/)() override | Rastgele bir başlangıç değeri oluşturur ve bunu algoritmanın iç yapısına kaydeder. |
| [GenerateKey](./generatekey/)() override | Rastgele bir anahtar oluşturur ve bunu algoritmanın iç yapısına kaydeder. |
## Ayrıca Bakınız

* Class [Rijndael](../rijndael/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
