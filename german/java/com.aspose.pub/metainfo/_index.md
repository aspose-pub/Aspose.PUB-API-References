---
title: "MetaInfo"
second_title: "Aspose.PUB for Java API-Referenz"
description: "Basisklasse für Zusammenfassungs‑Info‑Objekte"
type: docs
weight: 16
url: /de/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Basisklasse für Zusammenfassungs‑Info‑Objekte
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Roh-Byte-Reihenfolge |
| [isLittleEndian()](#isLittleEndian--) | Ist little endian |
| [getVersion()](#getVersion--) | Versionswert |
| [getSysID()](#getSysID--) | Systemidentifikator |
| [getClsid()](#getClsid--) | CLSID-Identifikator |
| [getFMTID()](#getFMTID--) | FMTID-Identifikator |
| [getPropsCount()](#getPropsCount--) | Anzahl der Eigenschaften |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Bezeichner von Eigenschaften |
| [getProperty(long id)](#getProperty-long-) | Liest Eigenschaft nach übergebener ID |
| [getCodePage()](#getCodePage--) | Codepage-Bezeichner |
| [getLocale()](#getLocale--) | Gebietsschema-Bezeichner |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Roh-Byte-Reihenfolge

**Returns:**
int - int-Wert
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Ist little endian

**Returns:**
boolean - boolean-Wert
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Versionswert

**Returns:**
int - int-Wert
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Systemidentifikator

**Returns:**
long - long-Wert
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


CLSID-Identifikator

**Returns:**
java.util.UUID - java.util.UUID-Instanz
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


FMTID-Identifikator

**Returns:**
java.util.UUID - java.util.UUID-Instanz
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Anzahl der Eigenschaften

**Returns:**
int - int-Wert
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Bezeichner von Eigenschaften

**Returns:**
java.util.List<java.lang.Long> - Liste von Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Liest Eigenschaft nach übergebener ID

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | long | Eigenschaftsbezeichner |

**Returns:**
java.lang.Object - Eigenschaftswert
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Codepage-Bezeichner

**Returns:**
short - short-Wert
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Gebietsschema-Bezeichner

**Returns:**
long - long-Wert
