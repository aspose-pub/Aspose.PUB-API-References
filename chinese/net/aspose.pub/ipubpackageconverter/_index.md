---
title: "接口 IPubPackageConverter"
second_title: "Aspose.PUB for .NET API 参考"
description: "Aspose.Pub.IPubPackageConverter 接口。声明将多个 Publisher 文档转换为指定格式的功能"
type: docs
weight: 140
url: /zh/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

声明将多个 Publisher 文档转换为指定格式的功能。

```csharp
public interface IPubPackageConverter
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | 将 *inputDocumentCollection* 列表中的每个文档转换为指定格式，并将结果保存到相应的存储中。保存的存储类型由 *outputType* 参数指定。已转换文档的引用放置在返回的 [`PackageDocumentCollection`](../packagedocumentcollection/) 对象中。如果设置了 *mergeFiles* 标志，则所有已转换的文档将按它们在 *inputDocumentCollection* 列表中的顺序合并为单个文档。 |

### 另见

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


