---
title: "System::Text::ICUEncoding Klasse"
linktitle: "ICUEncoding"
second_title: "Aspose.PUB für C++"
description: "System::Text::ICUEncoding Klasse. ICU-basierte Codierungsimplementierung. NUR FÜR INTERNEN GEBRAUCH. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse stets mit einem System::SmartPtr‑Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2200
url: /de/cpp/system.text/icuencoding/
---
## ICUEncoding class


ICU-basierte Codierungsimplementierung. NUR FÜR INTERNEN GEBRAUCH. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse stets mit einem [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [GetByteCount](./getbytecount/)(const char_t *, int) override | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(const String\&) | RTTI. |
| virtual [GetByteCount](./getbytecount/)(ArrayPtr\<char_t\>) | RTTI. |
| [GetBytes](./getbytes/)(const char_t *, int, uint8_t *, int) override | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(const String\&, int, int, ArrayPtr\<uint8_t\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(const String\&) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<char_t\>) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| [GetCharCount](./getcharcount/)(const uint8_t *, int) override | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual [GetCharCount](./getcharcount/)(ArrayPtr\<uint8_t\>) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| [GetChars](./getchars/)(const uint8_t *, int, char_t *, int) override | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>, int, int) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual [GetChars](./getchars/)(ArrayPtr\<uint8_t\>) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| [GetDecoder](./getdecoder/)() override | Ermittelt einen Decoder, der Anfragen an dieses Objekt weiterleitet. |
| [GetEncoder](./getencoder/)() override | Ermittelt einen Encoder, der Anfragen an dieses Objekt weiterleitet. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Ermittelt die maximale Anzahl von Bytes, die zum Kodieren einer angegebenen Anzahl von Zeichen benötigt werden. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Ermittelt die maximale Anzahl von Zeichen, die zum Dekodieren einer angegebenen Anzahl von Bytes benötigt werden. |
| [GetPreamble](./getpreamble/)() override | Gibt eine Bytefolge zurück, die die Kodierung bezeichnet (z. B. BOM). |
| [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Konstruktor. |
| [operator==](./operator==/)(const ICUEncoding\&) const | Vergleicht Kodierungen anhand von Codepages. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardwert der Codepage. |
## Siehe auch

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
