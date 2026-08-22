---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Riferimento API di Aspose.PUB per .NET"
description: "Metodo IPubPackageConverter. Converte ogni documento dall'elenco inputDocumentCollection nel formato specificato e salva i risultati nello storage appropriato. Il tipo di storage in cui salvare è specificato dal parametro outputType. I riferimenti ai documenti convertiti sono inseriti nell'oggetto PackageDocumentCollection restituito. Se il flag mergeFiles è impostato, tutti i documenti convertiti verranno uniti in un unico documento nello stesso ordine in cui sono stati inseriti nell'elenco inputDocumentCollection."
type: docs
weight: 10
url: /it/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Converte ogni documento dall'elenco *inputDocumentCollection* nel formato specificato e salva i risultati nello storage appropriato. Il tipo di storage in cui salvare è specificato dal parametro *outputType*. I riferimenti ai documenti convertiti sono inseriti nell'oggetto restituito [`PackageDocumentCollection`](../../packagedocumentcollection/). Se il flag *mergeFiles* è impostato, tutti i documenti convertiti verranno uniti in un unico documento nello stesso ordine in cui sono stati inseriti nell'elenco *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Raccolta di documenti di input. |
| mergeFiles | Boolean | Specifica se unire tutti i documenti di output in un unico documento. |
| outputFormat | PubExportFormats | Formato di output. |
| outputType | PubDocumentType | Tipo di storage di output. |

### Valore restituito

Riferimenti ai documenti convertiti nell'oggetto [`PackageDocumentCollection`](../../packagedocumentcollection/).

### Vedi anche

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


