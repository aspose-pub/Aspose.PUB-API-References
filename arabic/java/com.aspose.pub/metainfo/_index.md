---
title: "MetaInfo"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "الفئة الأساسية لكائنات معلومات الملخص"
type: docs
weight: 16
url: /ar/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

الفئة الأساسية لكائنات معلومات الملخص
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | ترتيب البايت الخام |
| [isLittleEndian()](#isLittleEndian--) | هو little endian |
| [getVersion()](#getVersion--) | قيمة الإصدار |
| [getSysID()](#getSysID--) | معرف النظام |
| [getClsid()](#getClsid--) | معرف CLSID |
| [getFMTID()](#getFMTID--) | معرف FMTID |
| [getPropsCount()](#getPropsCount--) | عدد الخصائص |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | معرفات الخصائص |
| [getProperty(long id)](#getProperty-long-) | يحصل على الخاصية بالمعرف الممرر |
| [getCodePage()](#getCodePage--) | معرف صفحة الشيفرة |
| [getLocale()](#getLocale--) | معرف اللغة |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


ترتيب البايت الخام

**Returns:**
int - قيمة int
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


هو little endian

**Returns:**
boolean - قيمة boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


قيمة الإصدار

**Returns:**
int - قيمة int
### getSysID() {#getSysID--}
```
public final long getSysID()
```


معرف النظام

**Returns:**
long - قيمة long
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


معرف CLSID

**Returns:**
java.util.UUID - نسخة java.util.UUID
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


معرف FMTID

**Returns:**
java.util.UUID - نسخة java.util.UUID
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


عدد الخصائص

**Returns:**
int - قيمة int
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


معرفات الخصائص

**Returns:**
java.util.List<java.lang.Long> - قائمة من Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


يحصل على الخاصية بالمعرف الممرر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| معرف | طويل | معرف الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


معرف صفحة الشيفرة

**Returns:**
short - قيمة قصيرة
### getLocale() {#getLocale--}
```
public final long getLocale()
```


معرف اللغة

**Returns:**
long - قيمة long
