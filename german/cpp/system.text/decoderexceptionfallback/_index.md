---
title: "System::Text::DecoderExceptionFallback Klasse"
linktitle: "DecoderExceptionFallback"
second_title: "Aspose.PUB für C++"
description: "System::Text::DecoderExceptionFallback Klasse. Stellt eine Ausnahmewurf‑Fallback‑Strategie bereit. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.text/decoderexceptionfallback/
---
## DecoderExceptionFallback class


Stellt eine Ausnahmewurf‑Fallback‑Strategie bereit. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)‑Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DecoderExceptionFallback : public System::Text::DecoderFallback
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CreateFallbackBuffer](./createfallbackbuffer/)() override | Erstellt einen Fallback-Puffer. |
| [get_MaxCharCount](./get_maxcharcount/)() const override | Ermittelt die maximale Anzahl von Zeichen, die die Instanz zurückgeben kann. |
## Siehe auch

* Class [DecoderFallback](../decoderfallback/)
* Namespace [System::Text](../)
* Library [Aspose.PUB for C++](../../)
