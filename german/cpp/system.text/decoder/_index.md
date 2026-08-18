---
title: "System::Text::Decoder Klasse"
linktitle: "Decoder"
second_title: "Aspose.PUB für C++"
description: "System::Text::Decoder Klasse. Kapselt die Dekodierung einer Bytesequenz in eine Zeichensequenz. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 200
url: /de/cpp/system.text/decoder/
---
## Decoder class


Kapselt die Dekodierung einer Bytesequenz in eine Zeichensequenz. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Decoder : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Convert](./convert/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) | Konvertiert Bytes in Zeichen. |
| virtual [Convert](./convert/)(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) | Konvertiert Bytes in Zeichen. |
| [get_Fallback](./get_fallback/)() const | Gibt den Fehlerbehandlungs‑Fallback zurück. |
| [get_FallbackBuffer](./get_fallbackbuffer/)() const | Gibt den Fallback-Puffer zurück. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int, bool) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden. |
| virtual [GetCharCount](./getcharcount/)(const uint8_t *, int, bool) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Puffers benötigt werden. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Gibt die Zeichen zurück, die beim Dekodieren eines Puffers entstehen. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) | Gibt die Zeichen zurück, die beim Dekodieren eines Puffers entstehen. |
| virtual [GetChars](./getchars/)(const uint8_t *, int, char_t *, int, bool) | Gibt die Zeichen zurück, die beim Dekodieren eines Puffers entstehen. |
| virtual [Reset](./reset/)() | Löscht den internen Zustand des Decoders. |
| [set_Fallback](./set_fallback/)(const DecoderFallbackPtr\&) | Setzt den Fehlerbehandlungs‑Fallback. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
