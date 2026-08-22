---
title: "MetaInfo"
second_title: "Aspose.PUB для Java справочник API"
description: "Базовый класс для объектов сводной информации."
type: docs
weight: 16
url: /ru/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Базовый класс для объектов сводной информации.
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Исходный порядок байтов |
| [isLittleEndian()](#isLittleEndian--) | Является little endian |
| [getVersion()](#getVersion--) | Значение версии |
| [getSysID()](#getSysID--) | Идентификатор системы |
| [getClsid()](#getClsid--) | Идентификатор CLSID |
| [getFMTID()](#getFMTID--) | Идентификатор FMTID |
| [getPropsCount()](#getPropsCount--) | Количество свойств |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Идентификаторы свойств |
| [getProperty(long id)](#getProperty-long-) | Получает свойство по переданному ID |
| [getCodePage()](#getCodePage--) | Идентификатор кодовой страницы |
| [getLocale()](#getLocale--) | Идентификатор локали |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Исходный порядок байтов

**Returns:**
int - значение int
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Является little endian

**Returns:**
boolean - значение boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Значение версии

**Returns:**
int - значение int
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Идентификатор системы

**Returns:**
long - значение long
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


Идентификатор CLSID

**Returns:**
java.util.UUID - экземпляр java.util.UUID
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


Идентификатор FMTID

**Returns:**
java.util.UUID - экземпляр java.util.UUID
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Количество свойств

**Returns:**
int - значение int
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Идентификаторы свойств

**Returns:**
java.util.List<java.lang.Long> - Список Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Получает свойство по переданному ID

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| идентификатор | long | идентификатор свойства |

**Returns:**
java.lang.Object - значение свойства
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Идентификатор кодовой страницы

**Returns:**
short - значение short
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Идентификатор локали

**Returns:**
long - значение long
