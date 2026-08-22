---
title: "Document"
second_title: "Aspose.PUB для Java справочник API"
description: "Представляет документ PUB, содержащий все поля и соответствующие значения"
type: docs
weight: 13
url: /ru/java/com.aspose.pub/document/
---
**Inheritance:**
java.lang.Object
```
public class Document
```

Представляет документ PUB, содержит все поля и соответствующие значения.
## Методы

| Метод | Описание |
| --- | --- |
| [getSummaryInfo()](#getSummaryInfo--) | Сводная информация |
| [setSummaryInfo(SummaryInfo value)](#setSummaryInfo-com.aspose.pub.SummaryInfo-) | Устанавливает сводную информацию |
| [getDocumentSummaryInfo()](#getDocumentSummaryInfo--) | Сводная информация о документе |
| [setDocSummaryInfo(DocSummaryInfo value)](#setDocSummaryInfo-com.aspose.pub.DocSummaryInfo-) | Устанавливает сводную информацию о документе |
| [getWidth()](#getWidth--) | Ширина документа в метриках PUB (EMUs) |
| [getHeight()](#getHeight--) | Высота документа в метриках PUB (EMUs) |
| [getDefaultTextStyles()](#getDefaultTextStyles--) | Массив стилей текста по умолчанию |
| [addDefaultTextStyle(TextStyle value)](#addDefaultTextStyle-com.aspose.pub.TextStyle-) | Добавляет стиль текста по умолчанию |
| [getDefaultParagraphStyles()](#getDefaultParagraphStyles--) | Массив стилей абзацев по умолчанию |
| [addDefaultParagraphStyle(ParagraphStyle value)](#addDefaultParagraphStyle-com.aspose.pub.ParagraphStyle-) | Добавляет стиль абзаца по умолчанию |
| [getFieldCount()](#getFieldCount--) | Количество всех полей |
| [getFontNames()](#getFontNames--) | Массив названий шрифтов |
| [getColors()](#getColors--) | Массив цветов |
### getSummaryInfo() {#getSummaryInfo--}
```
public final SummaryInfo getSummaryInfo()
```


Сводная информация

**Returns:**
[SummaryInfo](../../com.aspose.pub/summaryinfo) - SummaryInfo instance
### setSummaryInfo(SummaryInfo value) {#setSummaryInfo-com.aspose.pub.SummaryInfo-}
```
public final void setSummaryInfo(SummaryInfo value)
```


Устанавливает сводную информацию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SummaryInfo](../../com.aspose.pub/summaryinfo) | Значение Summary Info |

### getDocumentSummaryInfo() {#getDocumentSummaryInfo--}
```
public final DocSummaryInfo getDocumentSummaryInfo()
```


Сводная информация о документе

**Returns:**
[DocSummaryInfo](../../com.aspose.pub/docsummaryinfo) - DocSummaryInfo instance
### setDocSummaryInfo(DocSummaryInfo value) {#setDocSummaryInfo-com.aspose.pub.DocSummaryInfo-}
```
public final void setDocSummaryInfo(DocSummaryInfo value)
```


Устанавливает сводную информацию о документе

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DocSummaryInfo](../../com.aspose.pub/docsummaryinfo) | Значение сводной информации о документе |

### getWidth() {#getWidth--}
```
public final long getWidth()
```


Ширина документа в метриках PUB (EMUs)

**Returns:**
long - значение long
### getHeight() {#getHeight--}
```
public final long getHeight()
```


Высота документа в метриках PUB (EMUs)

**Returns:**
long - значение long
### getDefaultTextStyles() {#getDefaultTextStyles--}
```
public final TextStyle[] getDefaultTextStyles()
```


Массив стилей текста по умолчанию

**Returns:**
com.aspose.pub.TextStyle[] - массив экземпляров TextStyle
### addDefaultTextStyle(TextStyle value) {#addDefaultTextStyle-com.aspose.pub.TextStyle-}
```
public final void addDefaultTextStyle(TextStyle value)
```


Добавляет стиль текста по умолчанию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pub/textstyle) | стиль текста |

### getDefaultParagraphStyles() {#getDefaultParagraphStyles--}
```
public final ParagraphStyle[] getDefaultParagraphStyles()
```


Массив стилей абзацев по умолчанию

**Returns:**
com.aspose.pub.ParagraphStyle[] - массив экземпляров ParagraphStyle
### addDefaultParagraphStyle(ParagraphStyle value) {#addDefaultParagraphStyle-com.aspose.pub.ParagraphStyle-}
```
public final void addDefaultParagraphStyle(ParagraphStyle value)
```


Добавляет стиль абзаца по умолчанию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ParagraphStyle](../../com.aspose.pub/paragraphstyle) | стиль абзаца |

### getFieldCount() {#getFieldCount--}
```
public final int getFieldCount()
```


Количество всех полей

**Returns:**
int - значение int
### getFontNames() {#getFontNames--}
```
public final String[] getFontNames()
```


Массив названий шрифтов

**Returns:**
java.lang.String[] - массив значений String
### getColors() {#getColors--}
```
public final Color[] getColors()
```


Массив цветов

**Returns:**
java.awt.Color[] - массив экземпляров Color
