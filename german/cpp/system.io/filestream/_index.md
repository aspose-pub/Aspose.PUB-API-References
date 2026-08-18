---
title: "System::IO::FileStream Klasse"
linktitle: "FileStream"
second_title: "Aspose.PUB für C++"
description: "System::IO::FileStream Klasse. Stellt einen Dateistream dar, der synchrones und asynchrones Lesen und Schreiben unterstützt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1500
url: /de/cpp/system.io/filestream/
---
## FileStream class


Stellt einen Dateistream dar, der synchrones und asynchrones Lesen und Schreiben unterstützt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class FileStream : public System::IO::Stream
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Close](./close/)() override | Schließt das aktuelle [FileStream](./)-Objekt. |
| [FileStream](./filestream/)(const String\&, FileMode) | Erstellt eine neue Instanz der [FileStream](./)-Klasse und initialisiert sie mit den angegebenen Parametern. |
| [FileStream](./filestream/)(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) | Erstellt eine neue Instanz der [FileStream](./)-Klasse und initialisiert sie mit den angegebenen Parametern. |
| [FileStream](./filestream/)(const FileStream\&) |  |
| [Flush](./flush/)() override | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in die zugrunde liegende Datei. |
| [Flush](./flush/)(bool) | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in die zugrunde liegende Datei. Synonym für die Methode [Flush()](./flush/). |
| [get_CanRead](./get_canread/)() const override | Bestimmt, ob der Stream lesbar ist. |
| [get_CanSeek](./get_canseek/)() const override | Bestimmt, ob der Stream das Suchen unterstützt. |
| [get_CanWrite](./get_canwrite/)() const override | Bestimmt, ob der Stream schreibbar ist. |
| [get_Length](./get_length/)() const override | Gibt die Länge des Streams in Bytes zurück. |
| [get_Name](./get_name/)() const | Gibt den Namen der Datei zurück, die vom aktuellen [FileStream](./)-Objekt gekapselt wird. |
| [get_Position](./get_position/)() const override | Gibt die aktuelle Position des Streams zurück. |
| [operator=](./operator=/)(const FileStream\&) |  |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| [ReadByte](./readbyte/)() override | Liest ein einzelnes Byte aus dem Stream und gibt einen 32‑Bit‑Integer‑Wert zurück, der dem Wert des gelesenen Bytes entspricht. |
| [Seek](./seek/)(int64_t, SeekOrigin) override | Setzt die Position des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| [set_Position](./set_position/)(int64_t) override | Spült den Stream und setzt anschließend die Position des Streams. |
| [SetLength](./setlength/)(int64_t) override | Setzt die Länge des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| [WriteByte](./writebyte/)(uint8_t) override | Schreibt den angegebenen vorzeichenlosen 8‑Bit‑Ganzzahlwert in den Stream. |
| [~FileStream](./~filestream/)() | Destruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Standardwert für die Anzahl der Bytes, die während Lese- und Schreibvorgängen gepuffert werden. |
| static [Null](../stream/null/) | Ein Stream ohne zugrunde liegenden Speicher. |
## Siehe auch

* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
