---
title: "PubFactory"
second_title: "Référence API d'Aspose.PUB pour Java"
description: "Fabrique pour les objets PUB"
type: docs
weight: 18
url: /fr/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Fabrique pour les objets PUB
## Constructeurs

| Constructor | Description |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Crée un analyseur PUB pour le fichier PUB |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Crée un analyseur PUB pour le flux PUB |
| [createPdfConverter()](#createPdfConverter--) | Crée PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Crée un analyseur PUB pour le fichier PUB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Crée un analyseur PUB pour le flux PUB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pubStream | java.io.InputStream | flux contenant des données PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Crée PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
