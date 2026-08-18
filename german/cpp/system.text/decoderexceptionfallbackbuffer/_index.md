---
title: "System::Text::DecoderExceptionFallbackBuffer-Klasse"
linktitle: "DecoderExceptionFallbackBuffer"
second_title: "Aspose.PUB für C++"
description: "System::Text::DecoderExceptionFallbackBuffer-Klasse. Puffer für eine Ausnahme‑werfende Dekodierungs‑Fallback‑Strategie. Speichert tatsächlich nichts, wirft stattdessen. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben in C++."
type: docs
weight: 400
url: /de/cpp/system.text/decoderexceptionfallbackbuffer/
---
## DecoderExceptionFallbackBuffer class


[Buffer](../../system/buffer/) for exception-throwing decoding fallback strategy. Doesn't store anything actually, but throws instead. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DecoderExceptionFallbackBuffer : public System::Text::DecoderFallbackBuffer
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [DecoderExceptionFallbackBuffer](./decoderexceptionfallbackbuffer/)() | Konstruktor. |
| [Fallback](./fallback/)(ArrayPtr\<uint8_t\>, int) override | Behandelt Dekodierungsfehler. |
| [get_Remaining](./get_remaining/)() const override | Ermittelt die Anzahl verbleibender Zeichen. |
| [GetNextChar](./getnextchar/)() override | Liefert das nächste verfügbare Zeichen. |
| [MovePrevious](./moveprevious/)() override | Wechselt zum vorherigen Zeichen. |
## Siehe auch

* Class [DecoderFallbackBuffer](../decoderfallbackbuffer/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
