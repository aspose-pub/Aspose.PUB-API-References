---
title: "PubFactory"
second_title: "Aspose.PUB для Java справочник API"
description: "Фабрика объектов PUB."
type: docs
weight: 18
url: /ru/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

Фабрика объектов PUB.
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | Создаёт парсер PUB для файла PUB |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | Создаёт парсер PUB для потока PUB |
| [createPdfConverter()](#createPdfConverter--) | Создаёт PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


Создаёт парсер PUB для файла PUB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | имя файла PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


Создаёт парсер PUB для потока PUB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pubStream | java.io.InputStream | поток с данными PUB |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


Создаёт PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
