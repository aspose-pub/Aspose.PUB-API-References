---
title: "MetaInfo"
second_title: "Aspose.PUB for Java API Referansı"
description: "Özet bilgi nesneleri için temel sınıf"
type: docs
weight: 16
url: /tr/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Özet bilgi nesneleri için temel sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Ham bayt sırası |
| [isLittleEndian()](#isLittleEndian--) | Küçük uçlu mu |
| [getVersion()](#getVersion--) | Sürüm değeri |
| [getSysID()](#getSysID--) | Sistem tanımlayıcısı |
| [getClsid()](#getClsid--) | CLSID tanımlayıcısı |
| [getFMTID()](#getFMTID--) | FMTID tanımlayıcısı |
| [getPropsCount()](#getPropsCount--) | Özellik sayısı |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Özelliklerin tanımlayıcıları |
| [getProperty(long id)](#getProperty-long-) | Geçilen ID ile özelliği alır |
| [getCodePage()](#getCodePage--) | Kod sayfası tanımlayıcısı |
| [getLocale()](#getLocale--) | Yerel tanımlayıcı |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Ham bayt sırası

**Returns:**
int - int değeri
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Küçük uçlu mu

**Returns:**
boolean - boolean değeri
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürüm değeri

**Returns:**
int - int değeri
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Sistem tanımlayıcısı

**Returns:**
long - long değeri
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


CLSID tanımlayıcısı

**Returns:**
java.util.UUID - java.util.UUID örneği
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


FMTID tanımlayıcısı

**Returns:**
java.util.UUID - java.util.UUID örneği
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Özellik sayısı

**Returns:**
int - int değeri
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Özelliklerin tanımlayıcıları

**Returns:**
java.util.List<java.lang.Long> - Long listesi
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Geçilen ID ile özelliği alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | long | özellik tanımlayıcısı |

**Returns:**
java.lang.Object - özellik değeri
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Kod sayfası tanımlayıcısı

**Returns:**
short - short değeri
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Yerel tanımlayıcı

**Returns:**
long - long değeri
