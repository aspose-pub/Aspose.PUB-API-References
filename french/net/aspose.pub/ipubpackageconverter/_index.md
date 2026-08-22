---
title: "Interface IPubPackageConverter"
second_title: "Référence de l'API Aspose.PUB pour .NET"
description: "Interface Aspose.Pub.IPubPackageConverter. Déclare la fonctionnalité de conversion de plusieurs documents Publisher vers un format spécifié."
type: docs
weight: 140
url: /fr/net/aspose.pub/ipubpackageconverter/
---
## IPubPackageConverter interface

Déclare la fonctionnalité de conversion de plusieurs documents Publisher vers un format spécifié.

```csharp
public interface IPubPackageConverter
```

## Méthodes

| Nom | Description |
| --- | --- |
| [ConvertToFormat](../../aspose.pub/ipubpackageconverter/converttoformat/)(PackageDocumentCollection, bool, PubExportFormats, PubDocumentType) | Convertit chaque document de la liste *inputDocumentCollection* vers le format spécifié et enregistre les résultats dans le stockage approprié. Le type de stockage à utiliser est spécifié par le paramètre *outputType*. Les références aux documents convertis sont placées dans l'objet [`PackageDocumentCollection`](../packagedocumentcollection/) retourné. Si le drapeau *mergeFiles* est activé, alors tous les documents convertis seront fusionnés en un seul document dans le même ordre que celui dans lequel ils ont été placés dans la liste *inputDocumentCollection*. |

### Voir aussi

* namespace [Aspose.Pub](../../aspose.pub/)
* assembly [Aspose.PUB](../../)


