---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Справочник API Aspose.PUB для .NET"
description: "Метод IPubPackageConverter. Преобразует каждый документ из списка inputDocumentCollection в указанный формат и сохраняет результаты в соответствующее хранилище. Тип хранилища для сохранения указывается параметром outputType. Ссылки на преобразованные документы помещаются в возвращаемый объект PackageDocumentCollection. Если флаг mergeFiles установлен, то все преобразованные документы будут объединены в один документ в том же порядке, в котором они были размещены в списке inputDocumentCollection."
type: docs
weight: 10
url: /ru/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Преобразует каждый документ из списка *inputDocumentCollection* в указанный формат и сохраняет результаты в соответствующее хранилище. Тип хранилища для сохранения указывается параметром *outputType*. Ссылки на преобразованные документы помещаются в возвращаемый объект [`PackageDocumentCollection`](../../packagedocumentcollection/). Если установлен флаг *mergeFiles*, то все преобразованные документы будут объединены в один документ в том же порядке, в котором они были размещены в списке *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Коллекция входных документов. |
| mergeFiles | Boolean | Указывает, следует ли объединять все выходные документы в один. |
| outputFormat | PubExportFormats | Формат вывода. |
| outputType | PubDocumentType | Тип хранилища вывода. |

### Возвращаемое значение

Ссылки на преобразованные документы в объекте [`PackageDocumentCollection`](../../packagedocumentcollection/).

### См. также

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


