---
title: "PubFactory"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "مصنع لكائنات PUB"
type: docs
weight: 18
url: /ar/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

مصنع لكائنات PUB
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | ينشئ محلل PUB لملف PUB |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | ينشئ محلل PUB لتدفق PUB |
| [createPdfConverter()](#createPdfConverter--) | ينشئ PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


ينشئ محلل PUB لملف PUB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم ملف PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


ينشئ محلل PUB لتدفق PUB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pubStream | java.io.InputStream | دفق مع بيانات PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


ينشئ PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
