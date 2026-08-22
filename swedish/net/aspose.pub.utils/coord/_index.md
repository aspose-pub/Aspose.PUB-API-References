---
title: "Klass Coord"
second_title: "Aspose.PUB för .NET API-referens"
description: "Aspose.Pub.Utils.Coord-klass. Denna klass är utformad för att representera data relaterade till koordinater för PUB-fält. Varje fält i PUB har koordinater och har två par koordinater: koordinater för övre vänstra hörnet XLeft YTop och koordinater för nedre högra hörnet XRight YBottom. Alla koordinater representeras i det speciella mätsystemet English Metric Unit (EMUs). Ytterligare metoder har lagts till i denna klass för att omvandla koordinatvärden från engelska måttenheter till tum"
type: docs
weight: 350
url: /sv/net/aspose.pub.utils/coord/
---
## Coord class

Denna klass är avsedd att representera data relaterade till koordinater för PUB-fält. Varje fält i PUB har koordinater som består av 2 par: koordinater för övre vänstra hörnet (XLeft, YTop) och koordinater för nedre högra hörnet (XRight, YBottom). Alla koordinater representeras i ett speciellt mätsystem – English Metric Unit(EMUs). Ytterligare metoder har lagts till i denna klass för att omvandla koordinatvärden från engelska måttenheter till tum.

```csharp
public class Coord : ICloneable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Coord](coord/#constructor)() | Konstruktor |
| [Coord](coord/#constructor_1)(int, int, int, int) | Konstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | X-koordinat för övre vänstra hörnet i EMU |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | X-koordinat för nedre högra hörnet i EMU |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Y-koordinat för nedre högra hörnet i EMU |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Y-koordinat för övre vänstra hörnet i EMU |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Beräknar figurens höjd (aktuellt Coord-objekt) och returnerar resultatet i tum |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Beräknar figurens bredd (aktuellt Coord-objekt) och returnerar resultatet i tum |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Omvandlar värdet för X-koordinaten från PUB:s naturliga mätsystem till tum |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Omvandlar värdet för X-koordinaten från PUB:s naturliga mätsystem till tum |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Omvandlar värdet för Y-koordinaten från PUB:s naturliga mätsystem till tum |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Omvandlar värdet för Y-koordinaten från PUB:s naturliga mätsystem till tum |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Skapade en kopia av objektet |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Returnerar höjden på det aktuella Coord-objektet i naturliga PUB-mått |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Returnerar bredden på det aktuella Coord-objektet i naturliga PUB-mått |

### Se även

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


