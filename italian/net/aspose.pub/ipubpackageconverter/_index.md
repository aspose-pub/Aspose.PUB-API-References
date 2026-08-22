---
title: "Interfaccia IPubPackageConverter"
second_title: "Riferimento API di Aspose.PUB per .NET"
description: "Interfaccia Aspose.Pub.IPubPackageConverter. Dichiarazione della funzionalità per convertire più documenti Publisher in un formato specificato."
type: docs
weight: 140
url: /it/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

Dichiara la funzionalità per convertire più documenti Publisher in un formato specificato.

```csharp
public interface IPubPackageConverter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | Converte ogni documento dalla lista *inputDocumentCollection* nel formato specificato e salva i risultati nello storage appropriato. Il tipo di storage in cui salvare è specificato dal parametro *outputType*. I riferimenti ai documenti convertiti sono inseriti nell'oggetto [`PackageDocumentCollection`](../packagedocumentcollection/) restituito. Se il flag *mergeFiles* è impostato, tutti i documenti convertiti verranno uniti in un unico documento nello stesso ordine in cui sono stati inseriti nella lista *inputDocumentCollection*. |

### Vedi anche

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


