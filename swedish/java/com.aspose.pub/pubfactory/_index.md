---
title: "PubFactory"
second_title: "Aspose.PUB för Java API-referens"
description: "Fabrik för PUB-objekt"
type: docs
weight: 18
url: /sv/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Fabrik för PUB-objekt
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Skapar PUB parser för PUB fil |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Skapar PUB parser för PUB ström |
| [createPdfConverter()](#createPdfConverter--) | Skapar PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Skapar PUB parser för PUB fil

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | PUB filnamn |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Skapar PUB parser för PUB ström

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pubStream | java.io.InputStream | ström med PUB data |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Skapar PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
