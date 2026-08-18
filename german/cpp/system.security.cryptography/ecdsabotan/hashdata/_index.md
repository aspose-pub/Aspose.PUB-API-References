---
title: "System::Security::Cryptography::ECDsaBotan::HashData Methode"
linktitle: "HashData"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::ECDsaBotan::HashData Methode. Berechnet den Hashwert des angegebenen Daten-Arrays mit dem angegebenen Hash-Algorithmus in C++."
type: docs
weight: 700
url: /de/cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Berechnet den Hash-Wert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | ByteArrayPtr | [Data](../../../system.data/) zum Hashen. |
| Versatz | int32_t | Versatz in **data**. |
| Anzahl | int32_t | Anzahl der Bytes zu hashieren. |
| hash_algorithm | HashAlgorithmName | Hash-Algorithmus. |

### ReturnValue

Gehashte Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Berechnet den Hash-Wert des angegebenen Binärstroms mit dem angegebenen Hash-Algorithmus.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | StreamPtr | Binärer Stream zum Hashen. |
| hash_algorithm | HashAlgorithmName | Hash-Algorithmus. |

### ReturnValue

Gehashte Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
