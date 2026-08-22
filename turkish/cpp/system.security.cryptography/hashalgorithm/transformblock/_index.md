---
title: "System::Security::Cryptography::HashAlgorithm::TransformBlock yöntemi"
linktitle: "TransformBlock"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::HashAlgorithm::TransformBlock yöntemi. C++'ta veri bloğunu işler ve veriyi çıktı dizisine kopyalar."
type: docs
weight: 800
url: /tr/cpp/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock method


Veri bloğunu işler ve veriyi çıkış dizisine kopyalar.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) veriyi okumak için. |
| inputOffset | int | Giriş tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |
| outputBuffer | ArrayPtr\<uint8_t\> | Verinin kopyalanacağı çıktı tamponu; kopyalama yapılmayacaksa nullptr. |
| outputOffset | int | Çıktı tamponu kayması. |

### ReturnValue

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
