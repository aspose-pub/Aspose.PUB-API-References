---
title: "System::Security::Cryptography::CipherMode enum"
linktitle: "CipherMode"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::CipherMode enum. C++'de blok şifreleme modu."
type: docs
weight: 5300
url: /tr/cpp/system.security.cryptography/ciphermode/
---
## CipherMode enum


Blok şifreleme modu.

```cpp
enum class CipherMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| CBC | 1 | Şifre blok zincirleme, mevcut bloğu önceki blokla birleştirerek şifrelemeyi iyileştirir. |
| ECB | 2 | Bloklar arası etkileşim olmayan elektronik kod kitabı modu; daha zayıf şifrelemeye yol açar. |
| OFB | 3 | Büyük giriş bloklarını küçük parçalar halinde işleyen çıktı geri besleme modu. |
| CFB | 4 | Büyük giriş bloklarını küçük parçalar halinde işleyen şifre geri besleme modu. Karıştırma kuralları OFB'den farklıdır. |
| CTS | 5 | Şifre metni çalma modu, son iki blok dışındaki tüm bloklarda CBC gibi davranır. |

## Ayrıca Bakınız

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PUB for C++](../../)
