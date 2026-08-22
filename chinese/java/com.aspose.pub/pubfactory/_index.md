---
title: "PubFactory"
second_title: "Aspose.PUB for Java API 参考"
description: "PUB 对象的工厂"
type: docs
weight: 18
url: /zh/java/com.aspose.pub/pubfactory/
---
**Inheritance:**
java.lang.Object
```
public class PubFactory
```

PUB 对象的工厂
## 构造函数

| Constructor | 描述 |
| --- | --- |
| [PubFactory()](#PubFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createParser(String fileName)](#createParser-java.lang.String-) | 创建用于 PUB 文件的 PUB 解析器 |
| [createParser(InputStream pubStream)](#createParser-java.io.InputStream-) | 创建用于 PUB 流的 PUB 解析器 |
| [createPdfConverter()](#createPdfConverter--) | 创建 PdfConverter |
### PubFactory() {#PubFactory--}
```
public PubFactory()
```


### createParser(String fileName) {#createParser-java.lang.String-}
```
public static IPubParser createParser(String fileName)
```


创建用于 PUB 文件的 PUB 解析器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | PUB 文件名 |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createParser(InputStream pubStream) {#createParser-java.io.InputStream-}
```
public static IPubParser createParser(InputStream pubStream)
```


创建用于 PUB 流的 PUB 解析器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pubStream | java.io.InputStream | 包含 PUB 数据的流 |

**Returns:**
[IPubParser](../../com.aspose.pub/ipubparser) - PUB parser
### createPdfConverter() {#createPdfConverter--}
```
public static IPdfConverter createPdfConverter()
```


创建 PdfConverter

**Returns:**
[IPdfConverter](../../com.aspose.pub/ipdfconverter) - PdfConverter
