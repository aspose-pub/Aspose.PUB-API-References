---
title: "Document"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "يمثل مستند PUB يحتوي على جميع الحقول والقيم ذات الصلة"
type: docs
weight: 13
url: /ar/java/com.aspose.pub/document/
---
**Inheritance:**
java.lang.Object
```
public class Document
```

يمثل مستند PUB، يحتفظ بجميع الحقول والقيم ذات الصلة
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSummaryInfo()](#getSummaryInfo--) | معلومات الملخص |
| [setSummaryInfo(SummaryInfo value)](#setSummaryInfo-com.aspose.pub.SummaryInfo-) | يضبط معلومات الملخص |
| [getDocumentSummaryInfo()](#getDocumentSummaryInfo--) | معلومات ملخص المستند |
| [setDocSummaryInfo(DocSummaryInfo value)](#setDocSummaryInfo-com.aspose.pub.DocSummaryInfo-) | يضبط معلومات ملخص المستند |
| [getWidth()](#getWidth--) | عرض المستند بوحدات PUB (EMUs) |
| [getHeight()](#getHeight--) | ارتفاع المستند بوحدات PUB (EMUs) |
| [getDefaultTextStyles()](#getDefaultTextStyles--) | مصفوفة أنماط النص الافتراضية |
| [addDefaultTextStyle(TextStyle value)](#addDefaultTextStyle-com.aspose.pub.TextStyle-) | يضيف نمط نص افتراضي |
| [getDefaultParagraphStyles()](#getDefaultParagraphStyles--) | مصفوفة أنماط الفقرة الافتراضية |
| [addDefaultParagraphStyle(ParagraphStyle value)](#addDefaultParagraphStyle-com.aspose.pub.ParagraphStyle-) | يضيف نمط فقرة افتراضي |
| [getFieldCount()](#getFieldCount--) | عدد جميع الحقول |
| [getFontNames()](#getFontNames--) | مصفوفة أسماء الخطوط |
| [getColors()](#getColors--) | مصفوفة الألوان |
### getSummaryInfo() {#getSummaryInfo--}
```
public final SummaryInfo getSummaryInfo()
```


معلومات الملخص

**Returns:**
[SummaryInfo](../../com.aspose.pub/summaryinfo) - SummaryInfo instance
### setSummaryInfo(SummaryInfo value) {#setSummaryInfo-com.aspose.pub.SummaryInfo-}
```
public final void setSummaryInfo(SummaryInfo value)
```


يضبط معلومات الملخص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SummaryInfo](../../com.aspose.pub/summaryinfo) | قيمة معلومات الملخص |

### getDocumentSummaryInfo() {#getDocumentSummaryInfo--}
```
public final DocSummaryInfo getDocumentSummaryInfo()
```


معلومات ملخص المستند

**Returns:**
[DocSummaryInfo](../../com.aspose.pub/docsummaryinfo) - DocSummaryInfo instance
### setDocSummaryInfo(DocSummaryInfo value) {#setDocSummaryInfo-com.aspose.pub.DocSummaryInfo-}
```
public final void setDocSummaryInfo(DocSummaryInfo value)
```


يضبط معلومات ملخص المستند

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DocSummaryInfo](../../com.aspose.pub/docsummaryinfo) | قيمة معلومات ملخص المستند |

### getWidth() {#getWidth--}
```
public final long getWidth()
```


عرض المستند بوحدات PUB (EMUs)

**Returns:**
long - قيمة long
### getHeight() {#getHeight--}
```
public final long getHeight()
```


ارتفاع المستند بوحدات PUB (EMUs)

**Returns:**
long - قيمة long
### getDefaultTextStyles() {#getDefaultTextStyles--}
```
public final TextStyle[] getDefaultTextStyles()
```


مصفوفة أنماط النص الافتراضية

**Returns:**
com.aspose.pub.TextStyle[] - مصفوفة من مثيلات TextStyle
### addDefaultTextStyle(TextStyle value) {#addDefaultTextStyle-com.aspose.pub.TextStyle-}
```
public final void addDefaultTextStyle(TextStyle value)
```


يضيف نمط نص افتراضي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pub/textstyle) | نمط النص |

### getDefaultParagraphStyles() {#getDefaultParagraphStyles--}
```
public final ParagraphStyle[] getDefaultParagraphStyles()
```


مصفوفة أنماط الفقرة الافتراضية

**Returns:**
com.aspose.pub.ParagraphStyle[] - مصفوفة من مثيلات ParagraphStyle
### addDefaultParagraphStyle(ParagraphStyle value) {#addDefaultParagraphStyle-com.aspose.pub.ParagraphStyle-}
```
public final void addDefaultParagraphStyle(ParagraphStyle value)
```


يضيف نمط فقرة افتراضي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ParagraphStyle](../../com.aspose.pub/paragraphstyle) | نمط الفقرة |

### getFieldCount() {#getFieldCount--}
```
public final int getFieldCount()
```


عدد جميع الحقول

**Returns:**
int - قيمة int
### getFontNames() {#getFontNames--}
```
public final String[] getFontNames()
```


مصفوفة أسماء الخطوط

**Returns:**
java.lang.String[] - مصفوفة من قيم String
### getColors() {#getColors--}
```
public final Color[] getColors()
```


مصفوفة الألوان

**Returns:**
java.awt.Color[] - مصفوفة من مثيلات Color
