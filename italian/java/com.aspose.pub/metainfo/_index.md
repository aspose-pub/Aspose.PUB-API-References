---
title: "MetaInfo"
second_title: "Riferimento API di Aspose.PUB per Java"
description: "Classe base per gli oggetti di informazioni di riepilogo"
type: docs
weight: 16
url: /it/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Classe base per gli oggetti di informazioni di riepilogo
## Costruttori

| Constructor | Descrizione |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Ordine dei byte grezzo |
| [isLittleEndian()](#isLittleEndian--) | È little endian |
| [getVersion()](#getVersion--) | Valore della versione |
| [getSysID()](#getSysID--) | Identificatore di sistema |
| [getClsid()](#getClsid--) | Identificatore CLSID |
| [getFMTID()](#getFMTID--) | Identificatore FMTID |
| [getPropsCount()](#getPropsCount--) | Conteggio delle proprietà |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Identificatori delle proprietà |
| [getProperty(long id)](#getProperty-long-) | Ottiene la proprietà per ID fornito |
| [getCodePage()](#getCodePage--) | Identificatore della pagina di codice |
| [getLocale()](#getLocale--) | Identificatore locale |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Ordine dei byte grezzo

**Returns:**
int - valore int
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


È little endian

**Returns:**
boolean - valore boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Valore della versione

**Returns:**
int - valore int
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Identificatore di sistema

**Returns:**
long - valore long
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


Identificatore CLSID

**Returns:**
java.util.UUID - istanza java.util.UUID
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


Identificatore FMTID

**Returns:**
java.util.UUID - istanza java.util.UUID
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Conteggio delle proprietà

**Returns:**
int - valore int
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Identificatori delle proprietà

**Returns:**
java.util.List<java.lang.Long> - Elenco di Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Ottiene la proprietà per ID fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | long | identificatore della proprietà |

**Returns:**
java.lang.Object - valore della proprietà
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Identificatore della pagina di codice

**Returns:**
short - valore short
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Identificatore locale

**Returns:**
long - valore long
