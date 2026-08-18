---
title: "System::Drawing::Text::FontCollection Klasse"
linktitle: "FontCollection"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Text::FontCollection Klasse. Eine Basisklasse für installierte und private Schriftartensammlungen. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.drawing.text/fontcollection/
---
## FontCollection class


Eine Basisklasse für installierte und private Schriftartensammlungen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class FontCollection : public System::IDisposable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Dispose](./dispose/)() override | Gibt die vom aktuellen Objekt erworbenen Betriebssystemressourcen frei. |
| virtual [get_Families](./get_families/)() | Gibt ein Array von [FontFamily](../../system.drawing/fontfamily/) Objekten zurück, die mit der vom aktuellen Objekt dargestellten Schrift-Sammlung verknüpft sind. |
## Siehe auch

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PUB for C++](../../)
