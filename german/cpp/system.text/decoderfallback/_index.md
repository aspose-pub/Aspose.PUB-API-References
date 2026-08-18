---
title: "System::Text::DecoderFallback Klasse"
linktitle: "DecoderFallback"
second_title: "Aspose.PUB für C++"
description: "System::Text::DecoderFallback Klasse. Stellt eine Fallback‑API bereit, um Dekodierungsfehler zu behandeln. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 500
url: /de/cpp/system.text/decoderfallback/
---
## DecoderFallback class


Stellt eine Fallback‑API bereit, um Dekodierungsfehler zu behandeln. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DecoderFallback : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [CreateFallbackBuffer](./createfallbackbuffer/)() | Liefert den Puffer, der dem Fallback‑Algorithmus zugeordnet ist. |
| static [get_ExceptionFallback](./get_exceptionfallback/)() | Liefert die standardmäßige Ausnahme‑Fallback‑Implementierung. |
| virtual [get_MaxCharCount](./get_maxcharcount/)() const | Liefert die maximale Anzahl von Zeichen, die vom Fallback zurückgegeben werden können. |
| static [get_ReplacementFallback](./get_replacementfallback/)() | Liefert die standardmäßige Ersetzungs‑Fallback‑Implementierung. |
| static [get_StandardSafeFallback](./get_standardsafefallback/)() | Liefert die standardmäßige sichere Standard‑Fallback‑Implementierung. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
