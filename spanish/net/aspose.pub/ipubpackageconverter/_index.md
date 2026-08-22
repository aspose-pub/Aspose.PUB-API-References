---
title: "Interfaz IPubPackageConverter"
second_title: "Referencia de API de Aspose.PUB para .NET"
description: "Interfaz Aspose.Pub.IPubPackageConverter. Declara la funcionalidad para convertir varios documentos Publisher a un formato especificado."
type: docs
weight: 140
url: /es/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

Declara la funcionalidad para convertir varios documentos Publisher a un formato especificado.

```csharp
public interface IPubPackageConverter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | Convierte cada documento de la lista *inputDocumentCollection* al formato especificado y guarda los resultados en el almacenamiento apropiado. El tipo de almacenamiento donde guardar se especifica mediante el parámetro *outputType*. Las referencias a los documentos convertidos se colocan en el objeto [`PackageDocumentCollection`](../packagedocumentcollection/) devuelto. Si la bandera *mergeFiles* está activada, entonces todos los documentos convertidos se fusionarán en un solo documento en el mismo orden en que fueron colocados en la lista *inputDocumentCollection*. |

### Ver también

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


