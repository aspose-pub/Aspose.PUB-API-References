---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Aspose.PUB for .NET API 参考"
description: "IPubPackageConverter 方法。将 inputDocumentCollection 列表中的每个文档转换为指定格式，并将结果保存到相应的存储中。保存的存储类型由 outputType 参数指定。已转换文档的引用放置在返回的 PackageDocumentCollection 对象中。如果设置了 mergeFiles 标志，则所有已转换的文档将按它们在 inputDocumentCollection 列表中的顺序合并为单个文档。"
type: docs
weight: 10
url: /zh/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

将 *inputDocumentCollection* 列表中的每个文档转换为指定格式，并将结果保存到相应的存储中。保存的存储类型由 *outputType* 参数指定。已转换文档的引用放置在返回的 [`PackageDocumentCollection`](../../packagedocumentcollection/) 对象中。如果设置了 *mergeFiles* 标志，则所有已转换的文档将按它们在 *inputDocumentCollection* 列表中的顺序合并为单个文档。

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | 输入文档的集合。 |
| mergeFiles | Boolean | 指定是否将所有输出文档合并为单个文档。 |
| outputFormat | PubExportFormats | 输出格式。 |
| outputType | PubDocumentType | 输出存储类型。 |

### 返回值

已转换文档在 [`PackageDocumentCollection`](../../packagedocumentcollection/) 对象中的引用。

### 另见

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


