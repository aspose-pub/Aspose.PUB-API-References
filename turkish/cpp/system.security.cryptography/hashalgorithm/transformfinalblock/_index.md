---
title: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock yöntemi"
linktitle: "TransformFinalBlock"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::HashAlgorithm::TransformFinalBlock yöntemi. C++'ta verinin son bloğunu işler ve karmayı hesaplar."
type: docs
weight: 900
url: /tr/cpp/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock method


Son veri bloğunu işler ve hash'i hesaplar.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) veriyi okumak için. |
| inputOffset | int | Giriş tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |

### ReturnValue

Tüm veri dizisi için hesaplanan karma.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
