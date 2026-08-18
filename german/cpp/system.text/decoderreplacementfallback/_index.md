---
title: "System::Text::DecoderReplacementFallback Klasse"
linktitle: "DecoderReplacementFallback"
second_title: "Aspose.PUB für C++"
description: "System::Text::DecoderReplacementFallback Klasse. Bietet eine Fallback‑Strategie, bei der ein fehlerhaftes Symbol durch einen Platzhalter ersetzt wird. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 700
url: /de/cpp/system.text/decoderreplacementfallback/
---
## DecoderReplacementFallback class


Bietet eine Fallback‑Strategie, bei der ein fehlerhaftes Symbol durch einen Platzhalter ersetzt wird. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DecoderReplacementFallback : public System::Text::DecoderFallback
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Erstellt einen Fallback-Puffer. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)() | Konstruktor, der die Standard‑„?“‑Ersetzungszeichenkette verwendet. |
| [DecoderReplacementFallback](./decoderreplacementfallback/)(const String\&) | Konstruktor. |
| [get_DefaultString](./get_defaultstring/)() const | Liefert die Ersetzungszeichenkette. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Ermittelt die maximale Anzahl von Zeichen, die die Instanz zurückgeben kann. |
## Siehe auch

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
