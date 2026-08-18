---
title: "Aspose::Pub::Utils::Coord class"
linktitle: "Coord"
second_title: "Aspose.PUB für C++"
description: "Aspose::Pub::Utils::Coord class. Diese Klasse ist dafür konzipiert, Daten zu den Koordinaten von PUB-Feldern darzustellen. Jedes Feld in PUB enthält Koordinaten, die aus 2 Paaren bestehen: Koordinaten der oberen linken Ecke (XLeft, YTop) und Koordinaten der unteren rechten Ecke (XRight, YBottom). Alle Koordinaten werden in einem speziellen metrischen System – English Metric Unit (EMUs) – dargestellt. Zusätzliche Methoden wurden zu dieser Klasse hinzugefügt, um Koordinatenwerte von englischen metrischen Einheiten in Zoll in C++ zu transformieren."
type: docs
weight: 100
url: /de/cpp/aspose.pub.utils/coord/
---
## Coord class


Diese Klasse ist dazu gedacht, Daten zu den Koordinaten von PUB‑Feldern darzustellen. Jedes Feld in PUB enthält Koordinaten und hat 2 Koordinatenpaare: die Koordinaten der oberen linken Ecke (XLeft, YTop) und die Koordinaten der unteren rechten Ecke (XRight, YBottom). Alle Koordinaten werden in einem speziellen metrischen System – English Metric Unit (EMUs) – dargestellt. Zusätzliche Methoden wurden zu dieser Klasse hinzugefügt, um Koordinatenwerte von englischen metrischen Einheiten in Zoll umzuwandeln.

```cpp
class Coord : public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CalculateHeight](./calculateheight/)() | Berechnet die Höhe der Figur (aktuelles Coord-Objekt) und gibt das Ergebnis in Zoll zurück. |
| [CalculateWidth](./calculatewidth/)() | Berechnet die Breite der Figur (aktuelles Coord-Objekt) und gibt das Ergebnis in Zoll zurück. |
| [CalculateX](./calculatex/)(double) | Transformiert den Wert für die X-Koordinate vom natürlichen PUB-Metriksystem in Zoll. |
| [CalculateX](./calculatex/)() | Transformiert den Wert für die X-Koordinate vom natürlichen PUB-Metriksystem in Zoll. |
| [CalculateY](./calculatey/)(double) | Transformiert den Wert für die Y-Koordinate vom natürlichen PUB-Metriksystem in Zoll. |
| [CalculateY](./calculatey/)() | Transformiert den Wert für die Y-Koordinate vom natürlichen PUB-Metriksystem in Zoll. |
| [Clone](./clone/)() override | Kopie des Objekts erstellt. |
| [Coord](./coord/)() | Konstruktor. |
| [Coord](./coord/)(int32_t, int32_t, int32_t, int32_t) | Konstruktor. |
| [get_XLeft](./get_xleft/)() const | X‑Koordinate der oberen linken Ecke in EMUs. |
| [get_XRight](./get_xright/)() const | X‑Koordinate der unteren rechten Ecke in EMUs. |
| [get_YBottom](./get_ybottom/)() const | Y‑Koordinate der unteren rechten Ecke in EMUs. |
| [get_YTop](./get_ytop/)() const | Y‑Koordinate der oberen linken Ecke in EMUs. |
| [GetHeight](./getheight/)() | Gibt die Höhe des aktuellen [Coord](./)-Objekts in natürlichen PUB‑Metriken zurück. |
| [GetWidth](./getwidth/)() | Gibt die Breite des aktuellen [Coord](./)-Objekts in natürlichen PUB‑Metriken zurück. |
## Siehe auch

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pub::Utils](../)
* Library [Aspose.PUB for C++](../../)
