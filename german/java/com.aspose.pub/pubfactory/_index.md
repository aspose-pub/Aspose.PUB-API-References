---
title: "PubFactory"
second_title: "Aspose.PUB for Java API-Referenz"
description: "Fabrik für PUB‑Objekte"
type: docs
weight: 18
url: /de/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Fabrik für PUB‑Objekte
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Erstellt PUB-Parser für PUB-Datei |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Erstellt PUB-Parser für PUB-Stream |
| [createPdfConverter()](#createPdfConverter--) | Erstellt PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Erstellt PUB-Parser für PUB-Datei

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | PUB-Dateiname |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Erstellt PUB-Parser für PUB-Stream

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pubStream | java.io.InputStream | Stream mit PUB-Daten |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Erstellt PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
