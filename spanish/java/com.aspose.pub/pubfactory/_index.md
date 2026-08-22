---
title: "PubFactory"
second_title: "Referencia de API de Aspose.PUB para Java"
description: "Fábrica para objetos PUB"
type: docs
weight: 18
url: /es/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Fábrica para objetos PUB
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Crea el analizador PUB para archivo PUB |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Crea el analizador PUB para flujo PUB |
| [createPdfConverter()](#createPdfConverter--) | Crea PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Crea el analizador PUB para archivo PUB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | nombre de archivo PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Crea el analizador PUB para flujo PUB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pubStream | java.io.InputStream | flujo con datos PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Crea PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
