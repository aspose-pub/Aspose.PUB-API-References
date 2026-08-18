---
title: "System::IO::BufferedStream::Read Methode"
linktitle: "Lesen"
second_title: "Aspose.PUB für C++"
description: "System::IO::BufferedStream::Read Methode. Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte‑Array in C++."
type: docs
weight: 900
url: /de/cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte‑Array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | const ArrayPtr\<uint8_t\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden sollen |
| Versatz | int32_t | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnen soll |
| Anzahl | int32_t | Die Anzahl der zu lesenden Bytes |

### ReturnValue

Die Anzahl der gelesenen Bytes

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Liest die angegebene Anzahl von Bytes aus dem zugrunde liegenden Stream und schreibt sie in das angegebene Byte‑Array.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | const System::Details::ArrayView\<uint8_t\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden sollen |
| Versatz | int32_t | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnen soll |
| Anzahl | int32_t | Die Anzahl der zu lesenden Bytes |

### ReturnValue

Die Anzahl der gelesenen Bytes

## Siehe auch

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PUB for C++](../../../)
