---
title: "System::Text::UTF32Encoding Klasse"
linktitle: "UTF32Encoding"
second_title: "Aspose.PUB für C++"
description: "System::Text::UTF32Encoding Klasse. UTF-32-Codierung. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse stets mit einem System::SmartPtr‑Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2600
url: /de/cpp/system.text/utf32encoding/
---
## UTF32Encoding class


UTF-32-Codierung. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Umwickeln Sie diese Klasse stets mit einem [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone](./clone/)() override | Klont das Kodierungsobjekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Vergleicht mit Objekt. |
| [GetHashCode](./gethashcode/)() const override | Ermittelt den Hashcode der Kodierung. |
| [GetPreamble](./getpreamble/)() override | Ermittelt das Codepage-Präambel. |
| [operator==](./operator==/)(const UTF32Encoding\&) const | Vergleicht die Parameter von Codierungen. |
| [UTF32Encoding](./utf32encoding/)() | Konstruktor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool) | Konstruktor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool, bool) | Konstruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | Magische Zahl, die von [Windows](../../system.windows/) für die Big-Endian-UTF-32-Codepage-ID verwendet wird. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardwert der Codepage. |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | Magische Zahl, die von [Windows](../../system.windows/) für die Little-Endian-UTF-32-Codepage-ID verwendet wird. |
## Siehe auch

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
