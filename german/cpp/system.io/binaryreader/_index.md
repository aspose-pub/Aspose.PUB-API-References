---
title: "System::IO::BinaryReader class"
linktitle: "BinaryReader"
second_title: "Aspose.PUB für C++"
description: "System::IO::BinaryReader class. Stellt einen Leser dar, der primitive Datentypen als Binärdaten in einer bestimmten Kodierung liest. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 800
url: /de/cpp/system.io/binaryreader/
---
## BinaryReader class


Stellt einen Leser dar, der primitive Datentypen als Binärdaten in einer bestimmten Kodierung liest. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class BinaryReader : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&) | Konstruiert eine Instanz der Klasse [BinaryReader](./), die Daten aus dem angegebenen Stream unter Verwendung der UTF‑8‑Kodierung liest. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Konstruiert eine Instanz der Klasse [BinaryReader](./), die Daten aus dem angegebenen Stream unter Verwendung der angegebenen Kodierung liest. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) | Konstruiert eine Instanz der Klasse [BinaryReader](./), die Daten aus dem angegebenen Stream unter Verwendung der angegebenen Kodierung liest. |
| virtual [Close](./close/)() | Schließt das aktuelle [BinaryReader](./)-Objekt und den zugrunde liegenden Eingabestream. |
| [Dispose](./dispose/)() override | Gibt alle vom aktuellen Objekt verwendeten Ressourcen frei und schließt den zugrunde liegenden Stream. |
| virtual [get_BaseStream](./get_basestream/)() | Gibt den Eingabestream zurück. |
| virtual [PeekChar](./peekchar/)() | Liest ein einzelnes Zeichen aus dem Eingabestream, ohne den Lesekursor des Streams zu verändern. |
| virtual [Read](./read/)() | Liest ein einzelnes Zeichen aus dem Eingabestream. |
| virtual [Read](./read/)(ArrayPtr\<uint8_t\>, int, int) | Liest die angegebene Anzahl von Bytes aus dem Eingabestream und schreibt sie in das angegebene Byte‑Array. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Liest die angegebene Anzahl von Zeichen aus dem Eingabestream, konvertiert sie in die UTF‑16‑Kodierung und schreibt die resultierenden UTF‑16‑Zeichen in das angegebene Zeichen‑Array, beginnend an der angegebenen Position. |
| virtual [ReadBoolean](./readboolean/)() | Liest ein einzelnes Byte aus dem Eingabestream und gibt seine boolesche Darstellung zurück. |
| virtual [ReadByte](./readbyte/)() | Liest ein einzelnes Byte aus dem Eingabestream. |
| virtual [ReadBytes](./readbytes/)(int) | Liest die angegebene Anzahl von Bytes aus dem Eingabestream. |
| virtual [ReadChar](./readchar/)() | Liest ein einzelnes Zeichen aus dem Eingabestream. |
| virtual [ReadChars](./readchars/)(int) | Liest die angegebene Anzahl von Zeichen aus dem Eingabestream und gibt sie in UTF-16-Codierung zurück. |
| virtual [ReadDecimal](./readdecimal/)() | NICHT IMPLEMENTIERT. |
| virtual [ReadDouble](./readdouble/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als double‑Präzisions‑Gleitkommawert zurück. |
| virtual [ReadInt16](./readint16/)() | Liest 2 Bytes aus dem Eingabestream und gibt sie als 16‑Bit‑Ganzzahlwert zurück. |
| virtual [ReadInt32](./readint32/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als 32‑Bit‑Ganzzahlwert zurück. |
| virtual [ReadInt64](./readint64/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als 64‑Bit‑Ganzzahlwert zurück. |
| virtual [ReadSByte](./readsbyte/)() | Liest ein einzelnes Byte aus dem Eingabestream und gibt es als vorzeichenbehaftete 8‑Bit‑Ganzzahl zurück. |
| virtual [ReadSingle](./readsingle/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als single‑Präzisions‑Gleitkommawert zurück. |
| virtual [ReadString](./readstring/)() | Liest einen String aus dem aktuellen Stream. Der String wird mit der Länge vorangestellt, kodiert als ein Integer, sieben Bits auf einmal. |
| virtual [ReadUInt16](./readuint16/)() | Liest 2 Bytes aus dem Eingabestream und gibt sie als vorzeichenlose 16‑Bit‑Ganzzahl zurück. |
| virtual [ReadUInt32](./readuint32/)() | Liest 4 Bytes aus dem Eingabestream und gibt sie als vorzeichenlose 32‑Bit‑Ganzzahl zurück. |
| virtual [ReadUInt64](./readuint64/)() | Liest 8 Bytes aus dem Eingabestream und gibt sie als vorzeichenlose 64‑Bit‑Ganzzahl zurück. |
| virtual [~BinaryReader](./~binaryreader/)() | Destruktor. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PUB for C++](../../)
