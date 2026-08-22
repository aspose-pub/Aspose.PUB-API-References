---
title: "IPubPackageConverter.ConvertToFormat"
second_title: "Référence de l'API Aspose.PUB pour .NET"
description: "Méthode IPubPackageConverter. Convertit chaque document de la liste inputDocumentCollection au format spécifié et enregistre les résultats dans le stockage approprié. Le type de stockage à utiliser est spécifié par le paramètre outputType. Les références aux documents convertis sont placées dans l'objet PackageDocumentCollection retourné. Si le drapeau mergeFiles est activé, tous les documents convertis seront fusionnés en un seul document dans le même ordre que celui de la liste inputDocumentCollection."
type: docs
weight: 10
url: /fr/net/aspose.pub/ipubpackageconverter/converttoformat/
---
## IPubPackageConverter.ConvertToFormat method

Convertit chaque document de la liste *inputDocumentCollection* au format spécifié et enregistre les résultats dans le stockage approprié. Le type de stockage à utiliser est spécifié par le paramètre *outputType*. Les références aux documents convertis sont placées dans l'objet retourné [`PackageDocumentCollection`](../../packagedocumentcollection/). Si le drapeau *mergeFiles* est activé, tous les documents convertis seront fusionnés en un seul document dans le même ordre que celui de la liste *inputDocumentCollection*.

```csharp
public PackageDocumentCollection ConvertToFormat(PackageDocumentCollection inputDocumentCollection, 
    bool mergeFiles, PubExportFormats outputFormat, PubDocumentType outputType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputDocumentCollection | PackageDocumentCollection | Collection de documents d'entrée. |
| mergeFiles | Boolean | Spécifie s'il faut fusionner tous les documents de sortie en un seul. |
| outputFormat | PubExportFormats | Format de sortie. |
| outputType | PubDocumentType | Type de stockage de sortie. |

### Valeur de retour

Références aux documents convertis dans l'objet [`PackageDocumentCollection`](../../packagedocumentcollection/).

### Voir aussi

* class [PackageDocumentCollection](../../packagedocumentcollection/)
* enum [PubExportFormats](../../pubexportformats/)
* enum [PubDocumentType](../../pubdocumenttype/)
* interface [IPubPackageConverter](../)
* namespace [Aspose.Pub](../../ipubpackageconverter/)
* assembly [Aspose.PUB](../../../)


