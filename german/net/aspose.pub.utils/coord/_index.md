---
title: "Klasse Coord"
second_title: "Aspose.PUB für .NET API-Referenz"
description: "Aspose.Pub.Utils.Coord Klasse. Diese Klasse ist dazu entworfen, Daten zu den Koordinaten von PUB-Feldern darzustellen. Jedes Feld in PUB enthält Koordinaten und hat 2 Koordinatenpaare: die Koordinaten der oberen linken Ecke XLeft YTop und die Koordinaten der unteren rechten Ecke XRight YBottom. Alle Koordinaten werden in einem speziellen metrischen System, dem English Metric Unit (EMUs), dargestellt. Zusätzliche Methoden wurden in diese Klasse aufgenommen, um Koordinatenwerte von englischen metrischen Einheiten in Zoll umzuwandeln."
type: docs
weight: 350
url: /de/net/aspose.pub.utils/coord/
---
## Coord class

Diese Klasse ist dazu entworfen, Daten zu den Koordinaten von PUB-Feldern darzustellen. Jedes Feld in PUB enthält Koordinaten und hat 2 Koordinatenpaare: die Koordinaten der oberen linken Ecke (XLeft, YTop) und die Koordinaten der unteren rechten Ecke (XRight, YBottom). Alle Koordinaten werden in einem speziellen metrischen System – English Metric Unit (EMUs) – dargestellt. Zusätzliche Methoden wurden zu dieser Klasse hinzugefügt, um Koordinatenwerte von englischen metrischen Einheiten in Zoll umzuwandeln.

```csharp
public class Coord : ICloneable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Coord](coord/#constructor)() | Konstruktor |
| [Coord](coord/#constructor_1)(int, int, int, int) | Konstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | X-Koordinate der oberen linken Ecke in EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | X-Koordinate der unteren rechten Ecke in EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Y-Koordinate der unteren rechten Ecke in EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Y-Koordinate der oberen linken Ecke in EMUs |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Berechnet die Höhe der Figur (aktuelles Coord-Objekt) und gibt das Ergebnis in Zoll zurück |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Berechnet die Breite der Figur (aktuelles Coord-Objekt) und gibt das Ergebnis in Zoll zurück |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Wandelt den Wert für die X-Koordinate vom nativen PUB-Metriksystem in Zoll um |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Wandelt den Wert für die X-Koordinate vom nativen PUB-Metriksystem in Zoll um |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Wandelt den Wert für die Y-Koordinate vom nativen PUB-Metriksystem in Zoll um |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Wandelt den Wert für die Y-Koordinate vom nativen PUB-Metriksystem in Zoll um |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Kopie des Objekts erstellt |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Gibt die Höhe des aktuellen Coord-Objekts in natürlichen PUB-Metriken zurück |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Gibt die Breite des aktuellen Coord-Objekts in natürlichen PUB-Metriken zurück |

### Siehe auch

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


