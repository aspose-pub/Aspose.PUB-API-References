---
title: "System::Security::Cryptography::RijndaelManaged::CreateEncryptor yöntemi"
linktitle: "CreateEncryptor"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RijndaelManaged::CreateEncryptor yöntemi. C++'da algoritma nesnesi tarafından tanımlanan parametrelerle bir encryptor nesnesi oluşturur."
type: docs
weight: 200
url: /tr/cpp/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor() method


Algoritma nesnesi tarafından tanımlanan parametrelerle bir şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Açık parametrelerle bir şifreleyici nesnesi oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Byte dizisi biçiminde şifreleme anahtarı. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Byte dizisi biçiminde başlangıç değeri. |

### ReturnValue

Yeni oluşturulmuş encryptor nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
