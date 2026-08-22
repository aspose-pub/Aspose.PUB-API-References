---
title: "MetaInfo"
second_title: "Aspose.PUB för Java API-referens"
description: "Basklass för sammanfattningsinformationsobjekt"
type: docs
weight: 16
url: /sv/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Basklass för sammanfattningsinformationsobjekt
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Rå byteordning |
| [isLittleEndian()](#isLittleEndian--) | Är little endian |
| [getVersion()](#getVersion--) | Versionsvärde |
| [getSysID()](#getSysID--) | Systemidentifierare |
| [getClsid()](#getClsid--) | CLSID-identifierare |
| [getFMTID()](#getFMTID--) | FMTID-identifierare |
| [getPropsCount()](#getPropsCount--) | Antal egenskaper |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Identifierare för egenskaper |
| [getProperty(long id)](#getProperty-long-) | Hämtar egenskap efter angivet ID |
| [getCodePage()](#getCodePage--) | Kodsididentifierare |
| [getLocale()](#getLocale--) | Lokalidentifierare |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Rå byteordning

**Returns:**
int - int‑värde
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Är little endian

**Returns:**
boolean - boolean‑värde
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Versionsvärde

**Returns:**
int - int‑värde
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Systemidentifierare

**Returns:**
long - long‑värde
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


CLSID-identifierare

**Returns:**
java.util.UUID - java.util.UUID‑instans
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


FMTID-identifierare

**Returns:**
java.util.UUID - java.util.UUID‑instans
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Antal egenskaper

**Returns:**
int - int‑värde
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Identifierare för egenskaper

**Returns:**
java.util.List<java.lang.Long> - Lista med Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Hämtar egenskap efter angivet ID

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | long | egenskapsidentifierare |

**Returns:**
java.lang.Object - egenskapsvärde
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Kodsididentifierare

**Returns:**
short - kort värde
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Lokalidentifierare

**Returns:**
long - long‑värde
