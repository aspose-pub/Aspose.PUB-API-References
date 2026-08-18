---
title: "System::Text::UnicodeEncoding Klasse"
linktitle: "UnicodeEncoding"
second_title: "Aspose.PUB für C++"
description: "System::Text::UnicodeEncoding Klasse. Unicode-Codierung. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2500
url: /de/cpp/system.text/unicodeencoding/
---
## UnicodeEncoding class


Unicode-Codierung. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in den [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone](./clone/)() override | Klont das Kodierungsobjekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Vergleicht Kodierungen. |
| [GetHashCode](./gethashcode/)() const override | Erzeugt einen Hash der Codierung. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Ermittelt die maximale Anzahl von Bytes, die zum Kodieren einer angegebenen Anzahl von Zeichen benötigt werden. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Ermittelt die maximale Anzahl von Zeichen, die zum Dekodieren einer angegebenen Anzahl von Bytes benötigt werden. |
| [GetPreamble](./getpreamble/)() override | Gibt eine Bytefolge zurück, die die Kodierung bezeichnet (z. B. BOM). |
| [operator==](./operator==/)(const UnicodeEncoding\&) const | Vergleicht Codierungen nach Codepages und Flags. |
| [UnicodeEncoding](./unicodeencoding/)() | Konstruktor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool) | Konstruktor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool, bool) | Konstruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Big‑Endian‑Codepage‑Nummer. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardwert der Codepage. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Little‑Endian‑Codepage‑Nummer. |
## Siehe auch

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
