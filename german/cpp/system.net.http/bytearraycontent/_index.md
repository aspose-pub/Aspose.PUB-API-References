---
title: "System::Net::Http::ByteArrayContent class"
linktitle: "ByteArrayContent"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::ByteArrayContent class. Stellt HTTP-Inhalt als Byte-Array dar. Objekte dieser Klasse sollten ausschließlich mit der System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.net.http/bytearraycontent/
---
## ByteArrayContent class


Stellt HTTP-Inhalt als Byte-Array dar. Objekte dieser Klasse sollten ausschließlich mit der [System::MakeObject()](../../system/makeobject/)‑Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ByteArrayContent : public System::Net::Http::HttpContent
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>) | RTTI-Informationen. |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Konstruiert eine neue Instanz. |
| [TryComputeLength](./trycomputelength/)(int64_t\&) override | Versucht, die Länge des Byte-Arrays zu berechnen. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Die Standardkodierung. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Die maximale Anzahl an Bytes. |
## Siehe auch

* Class [HttpContent](../httpcontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PUB for C++](../../)
