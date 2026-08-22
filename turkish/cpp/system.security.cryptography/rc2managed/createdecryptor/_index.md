---
title: "System::Security::Cryptography::RC2Managed::CreateDecryptor yöntemi"
linktitle: "CreateDecryptor"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::RC2Managed::CreateDecryptor yöntemi. C++'de algoritma nesnesi tarafından tanımlanan parametrelerle bir deşifreleyici nesnesi oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor() method


Algoritma nesnesi tarafından tanımlanan parametrelerle bir şifre çözücü nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Açık parametrelerle bir şifre çözücü nesnesi oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | System::ArrayPtr\<uint8_t\> | Byte dizisi biçiminde şifreleme anahtarı. |
| rgbIV | System::ArrayPtr\<uint8_t\> | Byte dizisi biçiminde başlangıç değeri. |

### ReturnValue

Yeni oluşturulmuş decryptor nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
