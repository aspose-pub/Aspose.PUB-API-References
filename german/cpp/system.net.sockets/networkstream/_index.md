---
title: "System::Net::Sockets::NetworkStream class"
linktitle: "NetworkStream"
second_title: "Aspose.PUB für C++"
description: "System::Net::Sockets::NetworkStream class. Stellt den zugrunde liegenden Datenstrom für den Netzwerkzugriff bereit. Objekte dieser Klasse sollten nur über die System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Stellt den zugrunde liegenden Datenstrom für den Netzwerkzugriff bereit. Objekte dieser Klasse sollten nur über die [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class NetworkStream : public System::IO::Stream
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Startet einen asynchronen Lesevorgang. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Startet einen asynchronen Schreibvorgang. |
| [Close](./close/)(int) | Schließt die aktuelle Instanz, nachdem die angegebene Zeit abgelaufen ist. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Wartet, bis der angegebene asynchrone Lesevorgang abgeschlossen ist. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Beendet einen asynchronen Schreibvorgang. Wartet, bis der angegebene asynchrone Schreibvorgang abgeschlossen ist. |
| [Flush](./flush/)() override | Leert die Puffer dieses Streams und schreibt alle gepufferten Daten in den zugrunde liegenden Speicher. |
| [get_CanRead](./get_canread/)() const override | RTTI-Informationen. |
| [get_CanSeek](./get_canseek/)() const override | Bestimmt, ob der Stream das Suchen unterstützt. |
| [get_CanTimeout](./get_cantimeout/)() const override | Gibt einen Wert zurück, der bestimmt, ob der aktuelle Stream eine Zeitüberschreitung zulässt. |
| [get_CanWrite](./get_canwrite/)() const override | Bestimmt, ob der Stream schreibbar ist. |
| [get_DataAvailable](./get_dataavailable/)() const | Gibt einen Wert zurück, der anzeigt, ob Daten zum Lesen verfügbar sind. |
| [get_Length](./get_length/)() const override | Gibt die Länge des Streams in Bytes zurück. |
| [get_Position](./get_position/)() const override | Gibt die aktuelle Position des Streams zurück. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
| [get_Socket](./get_socket/)() | Ermittelt das zugrunde liegende [Socket](../socket/). |
| [get_WriteTimeout](./get_writetimeout/)() const override | Ermittelt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu schreiben, bevor ein Timeout eintritt. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Konstruiert eine neue Instanz. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Konstruiert eine neue Instanz. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Konstruiert eine neue Instanz. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Liest die angegebene Anzahl von Bytes aus dem Stream und schreibt sie in das angegebene Byte-Array. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Setzt die Position des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| [set_Position](./set_position/)(int64_t) override | Setzt die Position des Streams. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Setzt einen Wert, der bestimmt, ob der aktuelle Stream ein Timeout haben kann. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Setzt einen Wert in Millisekunden, der bestimmt, wie lange der Stream versucht zu lesen, bevor ein Timeout eintritt. |
| [SetLength](./setlength/)(int64_t) override | Setzt die Länge des Streams, die durch das aktuelle Objekt repräsentiert wird. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream. |
| virtual [~NetworkStream](./~networkstream/)() | Zerstört die aktuelle Instanz. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Ein Stream ohne zugrunde liegenden Speicher. |
## Siehe auch

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PUB for C++](../../)
