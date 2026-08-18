---
title: "System::String::ToByteArray-Methode"
linktitle: "ToByteArray"
second_title: "Aspose.PUB für C++"
description: "System::String::ToByteArray Methode. Konvertiert Zeichenkette oder Teilzeichenkette in ein Byte-Array in C++."
type: docs
weight: 4500
url: /de/cpp/system/string/tobytearray/
---
## String::ToByteArray method


Konvertiert Zeichenkette oder Teilzeichenkette in ein Byte‑Array.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=true) const
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int32_t | Startindex des Teilstrings. |
| length | int32_t | Länge des Teilstrings. |
| LE | bool | Wenn true, Zeichen mit little Endianness kodieren; andernfalls big Endianness verwenden. |

### ReturnValue

[Array](../../array/) containing bytes representing characters of the string.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PUB for C++](../../../)
