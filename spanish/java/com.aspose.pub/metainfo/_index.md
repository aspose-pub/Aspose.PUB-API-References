---
title: "MetaInfo"
second_title: "Referencia de API de Aspose.PUB para Java"
description: "Clase base para objetos de información resumida"
type: docs
weight: 16
url: /es/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Clase base para objetos de información resumida
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Orden de bytes sin procesar |
| [isLittleEndian()](#isLittleEndian--) | Es little endian |
| [getVersion()](#getVersion--) | Valor de versión |
| [getSysID()](#getSysID--) | Identificador del sistema |
| [getClsid()](#getClsid--) | Identificador CLSID |
| [getFMTID()](#getFMTID--) | Identificador FMTID |
| [getPropsCount()](#getPropsCount--) | Cantidad de propiedades |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Identificadores de propiedades |
| [getProperty(long id)](#getProperty-long-) | Obtiene la propiedad por ID pasado |
| [getCodePage()](#getCodePage--) | Identificador de página de códigos |
| [getLocale()](#getLocale--) | Identificador de configuración regional |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Orden de bytes sin procesar

**Returns:**
int - valor int
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Es little endian

**Returns:**
boolean - valor boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Valor de versión

**Returns:**
int - valor int
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Identificador del sistema

**Returns:**
long - valor long
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


Identificador CLSID

**Returns:**
java.util.UUID - instancia de java.util.UUID
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


Identificador FMTID

**Returns:**
java.util.UUID - instancia de java.util.UUID
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Cantidad de propiedades

**Returns:**
int - valor int
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Identificadores de propiedades

**Returns:**
java.util.List<java.lang.Long> - Lista de Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Obtiene la propiedad por ID pasado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | long | identificador de propiedad |

**Returns:**
java.lang.Object - valor de la propiedad
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Identificador de página de códigos

**Returns:**
short - valor short
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Identificador de configuración regional

**Returns:**
long - valor long
