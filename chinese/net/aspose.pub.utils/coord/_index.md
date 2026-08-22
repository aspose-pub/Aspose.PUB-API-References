---
title: "类 Coord"
second_title: "Aspose.PUB for .NET API 参考"
description: "Aspose.Pub.Utils.Coord 类。此类旨在表示与 PUB 字段坐标相关的数据。PUB 中的每个字段都有坐标，包含两对坐标：左上角坐标 XLeft YTop 和右下角坐标 XRight YBottom。所有坐标均以特殊度量系统 English Metric UnitEMUs 表示。此类添加了额外的方法，以将坐标值从英制度量单位转换为英寸。"
type: docs
weight: 350
url: /zh/net/aspose.pub.utils/coord/
---
## Coord class

此类旨在表示与 PUB 字段坐标相关的数据。PUB 中的每个字段都有坐标，包含两对坐标：左上角坐标 (XLeft, YTop) 和右下角坐标 (XRight, YBottom)。所有坐标均使用特殊度量系统——英制度量单位（EMUs）表示。此类中添加了额外的方法，以将英制度量单位的坐标值转换为英寸。

```csharp
public class Coord : ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Coord](coord/#constructor)() | 构造函数 |
| [Coord](coord/#constructor_1)(int, int, int, int) | 构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [XLeft](../../aspose.pub.utils/coord/xleft/) { get; } | 左上角的 X 坐标（单位：EMUs） |
| [XRight](../../aspose.pub.utils/coord/xright/) { get; } | 右下角的 X 坐标（单位：EMUs） |
| [YBottom](../../aspose.pub.utils/coord/ybottom/) { get; } | 右下角的 Y 坐标（单位：EMUs） |
| [YTop](../../aspose.pub.utils/coord/ytop/) { get; } | 左上角的 Y 坐标（单位：EMUs） |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CalculateHeight](../../aspose.pub.utils/coord/calculateheight/)() | 计算图形（当前 Coord 对象）的高度，并以英寸返回结果 |
| [CalculateWidth](../../aspose.pub.utils/coord/calculatewidth/)() | 计算图形（当前 Coord 对象）的宽度，并以英寸返回结果 |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex)() | 将 X 坐标值从自然 PUB 度量系统转换为英寸 |
| [CalculateX](../../aspose.pub.utils/coord/calculatex/#calculatex_1)(double) | 将 X 坐标值从自然 PUB 度量系统转换为英寸 |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey)() | 将 Y 坐标值从自然 PUB 度量系统转换为英寸 |
| [CalculateY](../../aspose.pub.utils/coord/calculatey/#calculatey_1)(double) | 将 Y 坐标值从自然 PUB 度量系统转换为英寸 |
| [Clone](../../aspose.pub.utils/coord/clone/)() | 已创建对象的副本 |
| [GetHeight](../../aspose.pub.utils/coord/getheight/)() | 返回当前 Coord 对象在自然 PUB 度量中的高度 |
| [GetWidth](../../aspose.pub.utils/coord/getwidth/)() | 返回当前 Coord 对象在自然 PUB 度量中的宽度 |

### 另见

* namespace [Aspose.Pub.Utils](../../aspose.pub.utils/)
* assembly [Aspose.PUB](../../)


