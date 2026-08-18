---
title: "System::IO::Stream Klasse"
linktitle: "Stream"
second_title: "Aspose.PUB für C++"
description: "System::IO::Stream Klasse. Eine Basisklasse für verschiedene Stream‑Implementierungen. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2100
url: /de/cpp/system.io/stream/
---
## Stream class


Eine Basisklasse für verschiedene Stream‑Implementierungen. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Stream : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Startet einen asynchronen Lesevorgang. |
| virtual [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) | Startet einen asynchronen Schreibvorgang. |
| virtual [Close](./close/)() | Schließt den Stream. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&) | Kopiert Bytes in den angegebenen Stream. |
| [CopyTo](./copyto/)(const SharedPtr\<Stream\>\&, int32_t) | Kopiert Bytes in den angegebenen Stream, wobei die angegebene Puffergröße verwendet wird. |
| [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den Stream. |
| virtual [EndRead](./endread/)(System::SharedPtr\<System::IAsyncResult\>) | Wartet, bis der angegebene asynchrone Lesevorgang abgeschlossen ist. |
| virtual [EndWrite](./endwrite/)(System::SharedPtr\<System::IAsyncResult\>) | Beendet einen asynchronen Schreibvorgang. Wartet, bis der angegebene asynchrone Schreibvorgang abgeschlossen ist. |
| virtual [Flush](./flush/)() | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in den zugrunde liegenden Speicher. |
| virtual [get_CanRead](./get_canread/)() const | Bestimmt, ob der Stream lesbar ist. |
| virtual [get_CanSeek](./get_canseek/)() const | Bestimmt, ob der Stream das Suchen unterstützt. |
| virtual [get_CanTimeout](./get_cantimeout/)() const | Gibt einen Wert zurück, der bestimmt, ob der aktuelle Stream eine Zeitüberschreitung zulässt. |
| virtual [get_CanWrite](./get_canwrite/)() const | Bestimmt, ob der Stream schreibbar ist. |
| virtual [get_Length](./get_length/)() const | Gibt die Länge des Streams in Bytes zurück. |
| virtual [get_Position](./get_position/)() const | Gibt die aktuelle Position des Streams zurück. |
| virtual [get_ReadTimeout](./get_readtimeout/)() const | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
| virtual [get_WriteTimeout](./get_writetimeout/)() const | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu schreiben, bevor ein Timeout eintritt. |
| virtual [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| virtual [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| [Read](./read/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| virtual [ReadByte](./readbyte/)() | Liest ein einzelnes Byte aus dem Stream und gibt einen 32‑Bit‑Integer‑Wert zurück, der dem Wert des gelesenen Bytes entspricht. |
| virtual [Seek](./seek/)(int64_t, SeekOrigin) | Setzt die Position des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| virtual [set_Position](./set_position/)(int64_t) | Setzt die Position des Streams. |
| virtual [set_ReadTimeout](./set_readtimeout/)(int) | Setzt einen Wert, der bestimmt, ob der aktuelle Stream ein Timeout haben kann. |
| virtual [set_WriteTimeout](./set_writetimeout/)(int) | Setzt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
| virtual [SetLength](./setlength/)(int64_t) | Setzt die Länge des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| virtual [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| [Write](./write/)(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| virtual [WriteByte](./writebyte/)(uint8_t) | Schreibt den angegebenen vorzeichenlosen 8‑Bit‑Ganzzahlwert in den Stream. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Null](./null/) | Ein Stream ohne zugrunde liegenden Speicher. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf diese Klasse. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
