---
title: "Интерфейс IPubPackageConverter"
second_title: "Справочник API Aspose.PUB для .NET"
description: "Интерфейс Aspose.Pub.IPubPackageConverter. Объявляет функциональность для преобразования нескольких документов Publisher в указанный формат."
type: docs
weight: 140
url: /ru/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

Объявляет функциональность для конвертации нескольких документов Publisher в указанный формат.

```csharp
public interface IPubPackageConverter
```

## Методы

| Имя | Описание |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | Преобразует каждый документ из списка *inputDocumentCollection* в указанный формат и сохраняет результаты в соответствующее хранилище. Тип хранилища для сохранения указывается параметром *outputType*. Ссылки на преобразованные документы помещаются в возвращаемый объект [`PackageDocumentCollection`](../packagedocumentcollection/). Если установлен флаг *mergeFiles*, все преобразованные документы будут объединены в один документ в том же порядке, в котором они были размещены в списке *inputDocumentCollection*. |

### См. также

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


