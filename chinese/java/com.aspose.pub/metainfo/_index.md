---
title: "MetaInfo"
second_title: "Aspose.PUB for Java API 参考"
description: "摘要信息对象的基类"
type: docs
weight: 16
url: /zh/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

摘要信息对象的基类
## 构造函数

| Constructor | 描述 |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | 原始字节序 |
| [isLittleEndian()](#isLittleEndian--) | 是小端序 |
| [getVersion()](#getVersion--) | 版本值 |
| [getSysID()](#getSysID--) | 系统标识符 |
| [getClsid()](#getClsid--) | CLSID 标识符 |
| [getFMTID()](#getFMTID--) | FMTID 标识符 |
| [getPropsCount()](#getPropsCount--) | 属性计数 |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | 属性标识符 |
| [getProperty(long id)](#getProperty-long-) | 根据传入的 ID 获取属性 |
| [getCodePage()](#getCodePage--) | 代码页标识符 |
| [getLocale()](#getLocale--) | 区域标识符 |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


原始字节序

**Returns:**
int - int 值
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


是小端序

**Returns:**
boolean - boolean 值
### getVersion() {#getVersion--}
```
public final int getVersion()
```


版本值

**Returns:**
int - int 值
### getSysID() {#getSysID--}
```
public final long getSysID()
```


系统标识符

**Returns:**
long - long 值
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


CLSID 标识符

**Returns:**
java.util.UUID - java.util.UUID 实例
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


FMTID 标识符

**Returns:**
java.util.UUID - java.util.UUID 实例
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


属性计数

**Returns:**
int - int 值
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


属性标识符

**Returns:**
java.util.List<java.lang.Long> - Long 列表
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


根据传入的 ID 获取属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标识符 | 长 | 属性标识符 |

**Returns:**
java.lang.Object - 属性值
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


代码页标识符

**Returns:**
short - 短值
### getLocale() {#getLocale--}
```
public final long getLocale()
```


区域标识符

**Returns:**
long - long 值
