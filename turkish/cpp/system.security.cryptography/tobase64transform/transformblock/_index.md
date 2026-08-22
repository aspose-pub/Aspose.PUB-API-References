---
title: "System::Security::Cryptography::ToBase64Transform::TransformBlock yöntemi"
linktitle: "TransformBlock"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::ToBase64Transform::TransformBlock yöntemi. C++'ta veri bloğunu işler ve veriyi çıktı dizisine kopyalar."
type: docs
weight: 800
url: /tr/cpp/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock method


Veri bloğunu işler ve veriyi çıkış dizisine kopyalar.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | System::ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) veriyi okumak için. |
| inputOffset | int32_t | Giriş tamponu ofseti. |
| inputCount | int32_t | İşlenecek bayt sayısı. |
| outputBuffer | System::ArrayPtr\<uint8_t\> | Verinin kopyalanacağı çıktı tamponu; kopyalama yapılmayacaksa nullptr. |
| outputOffset | int32_t | Çıktı tamponu kayması. |

### ReturnValue

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
