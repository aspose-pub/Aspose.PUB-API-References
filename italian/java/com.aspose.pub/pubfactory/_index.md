---
title: "PubFactory"
second_title: "Riferimento API di Aspose.PUB per Java"
description: "Fabbrica per oggetti PUB"
type: docs
weight: 18
url: /it/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Fabbrica per oggetti PUB
## Costruttori

| Constructor | Descrizione |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Crea il parser PUB per il file PUB |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Crea il parser PUB per lo stream PUB |
| [createPdfConverter()](#createPdfConverter--) | Crea PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Crea il parser PUB per il file PUB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome file PUB. |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Crea il parser PUB per lo stream PUB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pubStream | java.io.InputStream | flusso con dati PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Crea PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
