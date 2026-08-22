---
title: "PubFactory"
second_title: "Aspose.PUB for Java API Referansı"
description: "PUB nesneleri için fabrika"
type: docs
weight: 18
url: /tr/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

PUB nesneleri için fabrika
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | PUB dosyası için PUB ayrıştırıcı oluşturur |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | PUB akışı için PUB ayrıştırıcı oluşturur |
| [createPdfConverter()](#createPdfConverter--) | PdfConverter oluşturur |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


PUB dosyası için PUB ayrıştırıcı oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | PUB dosya adı |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


PUB akışı için PUB ayrıştırıcı oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pubStream | java.io.InputStream | PUB verileri içeren akış |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


PdfConverter oluşturur

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
