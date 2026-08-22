---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Referencia de API de Aspose.PUB para .NET"
description: "Método IPubPackageConverter. Convierte cada documento de la lista inputDocumentCollection al formato especificado y guarda los resultados en el almacenamiento apropiado. El tipo de almacenamiento para guardar se especifica mediante el parámetro outputType. Las referencias a los documentos convertidos se colocan en el objeto PackageDocumentCollection devuelto. Si la bandera mergeFiles está activada, entonces todos los documentos convertidos se fusionarán en un único documento en el mismo orden en que fueron colocados en la lista inputDocumentCollection."
type: docs
weight: 10
url: /es/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Convierte cada documento de la lista *inputDocumentCollection* al formato especificado y guarda los resultados en el almacenamiento apropiado. El tipo de almacenamiento para guardar se especifica mediante el parámetro *outputType*. Las referencias a los documentos convertidos se colocan en el objeto devuelto [`PackageDocumentCollection`](../../packagedocumentcollection/). Si la bandera *mergeFiles* está activada, entonces todos los documentos convertidos se fusionarán en un único documento en el mismo orden en que fueron colocados en la lista *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Colección de documentos de entrada. |
| mergeFiles | Boolean | Especifica si se deben fusionar todos los documentos de salida en uno único. |
| outputFormat | PubExportFormats | Formato de salida. |
| outputType | PubDocumentType | Tipo de almacenamiento de salida. |

### Valor devuelto

Referencias a los documentos convertidos en el objeto [`PackageDocumentCollection`](../../packagedocumentcollection/).

### Ver también

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


