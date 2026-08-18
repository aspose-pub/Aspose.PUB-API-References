---
title: "System::Text::EncoderFallback Klasse"
linktitle: "EncoderFallback"
second_title: "Aspose.PUB für C++"
description: "System::Text::EncoderFallback Klasse. Stellt eine Fallback-API zur Behandlung von Kodierungsfehlern bereit. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1200
url: /de/cpp/system.text/encoderfallback/
---
## EncoderFallback class


Stellt eine Fallback-API zur Behandlung von Kodierungsfehlern bereit. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)‑Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class EncoderFallback : public System::Object
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
