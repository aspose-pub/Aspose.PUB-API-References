---
title: "System::Security::Cryptography::ICryptoTransform::TransformBlock yöntemi"
linktitle: "TransformBlock"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::ICryptoTransform::TransformBlock yöntemi. C++'ta RTTI bilgisi."
type: docs
weight: 300
url: /tr/cpp/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock method


RTTI bilgisi.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
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
## Açıklamalar


Veri bloğunu işler ve veriyi çıkış dizisine kopyalar.
## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
