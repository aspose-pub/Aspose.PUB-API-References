---
title: "MetaInfo"
second_title: "Référence API d'Aspose.PUB pour Java"
description: "Classe de base pour les objets d'informations de résumé"
type: docs
weight: 16
url: /fr/java/com.aspose.pub/metainfo/
---
**Inheritance:**
java.lang.Object
```
public class MetaInfo
```

Classe de base pour les objets d'informations de résumé
## Constructeurs

| Constructor | Description |
| --- | --- |
| [MetaInfo()](#MetaInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRawByteOrder()](#getRawByteOrder--) | Ordre des octets brut |
| [isLittleEndian()](#isLittleEndian--) | Est little endian |
| [getVersion()](#getVersion--) | Valeur de version |
| [getSysID()](#getSysID--) | Identifiant du système |
| [getClsid()](#getClsid--) | Identifiant CLSID |
| [getFMTID()](#getFMTID--) | Identifiant FMTID |
| [getPropsCount()](#getPropsCount--) | Nombre de propriétés |
| [getPropsIdentifiers()](#getPropsIdentifiers--) | Identifiants des propriétés |
| [getProperty(long id)](#getProperty-long-) | Obtient la propriété par ID passé |
| [getCodePage()](#getCodePage--) | Identifiant de la page de code |
| [getLocale()](#getLocale--) | Identifiant de la locale |
### MetaInfo() {#MetaInfo--}
```
public MetaInfo()
```


### getRawByteOrder() {#getRawByteOrder--}
```
public final int getRawByteOrder()
```


Ordre des octets brut

**Returns:**
int - valeur int
### isLittleEndian() {#isLittleEndian--}
```
public final boolean isLittleEndian()
```


Est little endian

**Returns:**
boolean - valeur boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Valeur de version

**Returns:**
int - valeur int
### getSysID() {#getSysID--}
```
public final long getSysID()
```


Identifiant du système

**Returns:**
long - valeur long
### getClsid() {#getClsid--}
```
public final UUID getClsid()
```


Identifiant CLSID

**Returns:**
java.util.UUID - instance java.util.UUID
### getFMTID() {#getFMTID--}
```
public final UUID getFMTID()
```


Identifiant FMTID

**Returns:**
java.util.UUID - instance java.util.UUID
### getPropsCount() {#getPropsCount--}
```
public final int getPropsCount()
```


Nombre de propriétés

**Returns:**
int - valeur int
### getPropsIdentifiers() {#getPropsIdentifiers--}
```
public final List<Long> getPropsIdentifiers()
```


Identifiants des propriétés

**Returns:**
java.util.List<java.lang.Long> - Liste de Long
### getProperty(long id) {#getProperty-long-}
```
public final Object getProperty(long id)
```


Obtient la propriété par ID passé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| identifiant | long | identifiant de propriété |

**Returns:**
java.lang.Object - valeur de propriété
### getCodePage() {#getCodePage--}
```
public final short getCodePage()
```


Identifiant de la page de code

**Returns:**
short - valeur short
### getLocale() {#getLocale--}
```
public final long getLocale()
```


Identifiant de la locale

**Returns:**
long - valeur long
