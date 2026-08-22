---
title: "Classe Coord"
second_title: "Riferimento API di Aspose.PUB per .NET"
description: "Classe Aspose.Pub.Utils.Coord. Questa classe è progettata per rappresentare i dati relativi alle coordinate dei campi PUB. Ogni campo in PUB contiene coordinate e ha 2 coppie di coordinate: le coordinate dell'angolo superiore sinistro XLeft YTop e le coordinate dell'angolo inferiore destro XRight YBottom. Tutte le coordinate sono rappresentate in un sistema metrico speciale, l'English Metric Unit (EMUs). Sono stati aggiunti metodi aggiuntivi a questa classe per trasformare i valori delle coordinate dalle unità metriche inglesi in pollici"
type: docs
weight: 350
url: /it/net/aspose.pub.utils/coord/
---
## Coord class

Questa classe è progettata per rappresentare i dati relativi alle coordinate dei campi PUB. Ogni campo in PUB contiene coordinate e ha 2 coppie di coordinate: le coordinate dell'angolo superiore sinistro (XLeft, YTop) e le coordinate dell'angolo inferiore destro (XRight, YBottom). Tutte le coordinate sono rappresentate in un sistema metrico speciale - English Metric Unit(EMUs). Sono stati aggiunti metodi aggiuntivi a questa classe per trasformare i valori delle coordinate da unità metriche inglesi a pollici.

```csharp
public class Coord : ICloneable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Coord](coord/#constructor)() | Costruttore |
| [Coord](coord/#constructor_1)(int, int, int, int) | Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | Coordinata X dell'angolo superiore sinistro in EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | Coordinata X dell'angolo inferiore destro in EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Coordinata Y dell'angolo inferiore destro in EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Coordinata Y dell'angolo superiore sinistro in EMUs |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Calcola l'altezza della figura (oggetto Coord corrente) e restituisce il risultato in pollici |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Calcola la larghezza della figura (oggetto Coord corrente) e restituisce il risultato in pollici |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Trasforma il valore della coordinata X dal sistema metrico naturale di PUB in pollici |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Trasforma il valore della coordinata X dal sistema metrico naturale di PUB in pollici |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Trasforma il valore della coordinata Y dal sistema metrico naturale di PUB in pollici |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Trasforma il valore della coordinata Y dal sistema metrico naturale di PUB in pollici |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Copia dell'oggetto creata |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Restituisce l'altezza dell'oggetto Coord corrente in metriche naturali PUB |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Restituisce la larghezza dell'oggetto Coord corrente in metriche naturali PUB |

### Vedi anche

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


