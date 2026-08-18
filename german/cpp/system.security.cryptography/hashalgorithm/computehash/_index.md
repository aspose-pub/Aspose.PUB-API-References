---
title: "System::Security::Cryptography::HashAlgorithm::ComputeHash-Methode"
linktitle: "ComputeHash"
second_title: "Aspose.PUB für C++"
description: "System::Security::Cryptography::HashAlgorithm::ComputeHash-Methode. Hasht den Puffer in C++."
type: docs
weight: 200
url: /de/cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method


Hash‑Puffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | const ArrayPtr\<uint8_t\>\& | Quellpuffer. |

### ReturnValue

Berechneter Hash-Wert.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method


Slice des Hash‑Puffers.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | const ArrayPtr\<uint8_t\>\& | Quellpuffer. |
| Versatz | int | Versatz im Quellpuffer. |
| Anzahl | int | Anzahl der Bytes, die aus dem Quellpuffer verwendet werden sollen. |

### ReturnValue

Berechneter Hash-Wert.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method


Liest den Stream bis zum Ende und berechnet den Hash für die gelesenen Daten.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | SharedPtr\<IO::Stream\> const\& | Stream zum Lesen von Daten. |

### ReturnValue

Berechneter Hash-Wert für die gesamten Stream-Daten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PUB for C++](../../../)
