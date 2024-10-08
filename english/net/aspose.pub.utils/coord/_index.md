---
title: Class Coord
second_title: Aspose.PUB for .NET API Reference
description: Aspose.Pub.Utils.Coord class. This class designed to represent data related to coordinates of PUB fields. Every field in PUB holds coordinates has 2 pairs of coordinates coordinates of upperleft corner XLeft YTop and coordinates of bottomright cornerXRight YBottom. All coordinates represented in special metric system  English Metric UnitEMUs. Additional methods were added into this class to transform coordinate values from english metric units into inches
type: docs
weight: 350
url: /net/aspose.pub.utils/coord/
---
## Coord class

This class designed to represent data related to coordinates of PUB fields. Every field in PUB holds coordinates has 2 pairs of coordinates: coordinates of upper-left corner (XLeft, YTop) and coordinates of bottom-right corner(XRight, YBottom). All coordinates represented in special metric system - English Metric Unit(EMUs). Additional methods were added into this class to transform coordinate values from english metric units into inches.

```csharp
public class Coord : ICloneable
```

## Constructors

| Name | Description |
| --- | --- |
| [Coord](coord/#constructor)() | Constructor |
| [Coord](coord/#constructor_1)(int, int, int, int) | Constructor |

## Properties

| Name | Description |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | X-coordinate of upper-left corner in EMUs |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | X-coordinate of bottom-right corner in EMUs |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | Y-coordinate of bottom-right corner in EMUs |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | Y-coordinate of upper-left corner in EMUs |

## Methods

| Name | Description |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | Calculates height of figure(current Coord object) and returns result in inches |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | Calculates width of figure(current Coord object) and returns result in inches |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | Transforms value for X-coordinate from natural PUB metric system into inches |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | Transforms value for X-coordinate from natural PUB metric system into inches |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | Transforms value for Y-coordinate from natural PUB metric system into inches |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | Transforms value for Y-coordinate from natural PUB metric system into inches |
| [Clone](../../aspose.pub.utils/coord/clone/)() | Created copy of object |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | Returns height of current Coord object in natural PUB metrics |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | Returns width of current Coord object in natural PUB metrics |

### See Also

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


