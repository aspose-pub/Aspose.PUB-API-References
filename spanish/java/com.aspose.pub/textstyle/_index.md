---
title: "TextStyle"
second_title: "Referencia de API de Aspose.PUB para Java"
description: "Describe el estilo de texto PUB"
type: docs
weight: 23
url: /es/java/com.aspose.pub/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.pub.BaseStyle](../../com.aspose.pub/basestyle)
```
public class TextStyle extends BaseStyle
```

Describe el estilo de texto PUB
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextStyle()](#TextStyle--) | Constructor |
## Métodos

| Método | Descripción |
| --- | --- |
| [isBold()](#isBold--) | El texto está en negrita |
| [setIsBold(boolean value)](#setIsBold-boolean-) | Establece si el texto está en negrita |
| [isItalic()](#isItalic--) | El texto está en cursiva |
| [setIsItalic(boolean value)](#setIsItalic-boolean-) | Establece si el texto está en cursiva |
| [getUnderlineType()](#getUnderlineType--) | Tipo de subrayado para el texto |
| [setUnderlineType(byte value)](#setUnderlineType-byte-) | Establece el tipo de subrayado para el texto |
| [isOutline()](#isOutline--) | El texto está contorneado |
| [setIsOutline(boolean value)](#setIsOutline-boolean-) | Establece si el texto está contorneado |
| [isShadow()](#isShadow--) | El texto tiene sombra |
| [setIsShadow(boolean value)](#setIsShadow-boolean-) | Establece si el texto tiene sombra |
| [isSmallCapsMode()](#isSmallCapsMode--) | Modo de versalitas habilitado |
| [setIsSmallCapsMode(boolean value)](#setIsSmallCapsMode-boolean-) | Activa/desactiva el modo de versalitas para el texto |
| [isAllCapsMode()](#isAllCapsMode--) | Modo de mayúsculas activado |
| [setIsAllCapsMode(boolean value)](#setIsAllCapsMode-boolean-) | Activa/desactiva el modo de mayúsculas para el texto |
| [isEmboss()](#isEmboss--) | El texto está en relieve |
| [setIsEmboss(boolean value)](#setIsEmboss-boolean-) | Establece si el texto está en relieve |
| [isEngrave()](#isEngrave--) | El texto está grabado |
| [setIsEngrave(boolean value)](#setIsEngrave-boolean-) | Establece si el texto está grabado |
| [getRawTextSize()](#getRawTextSize--) | Tamaño del texto en métricas PUB (en EMU) |
| [setRawTextSize(int value)](#setRawTextSize-int-) | Establece el tamaño del texto en métricas PUB (en EMU) |
| [calculateTextSize()](#calculateTextSize--) | Calcula el tamaño del texto en puntos |
| [getColorIndex()](#getColorIndex--) | Obtiene el índice del color en la matriz Document.Colors |
| [setColorIndex(int value)](#setColorIndex-int-) | Establece el índice del color en la matriz Document.Colors |
| [getFontIndex()](#getFontIndex--) | Obtiene el índice del nombre de fuente en la matriz Document.FontNames |
| [setFontIndex(int value)](#setFontIndex-int-) | Establece el índice del nombre de fuente en la matriz Document.FontNames |
| [getSuperscriptType()](#getSuperscriptType--) | Tipo de superíndice |
| [setSuperscriptType(byte value)](#setSuperscriptType-byte-) | Establece el tipo de superíndice |
| [getScaleValue()](#getScaleValue--) | Valor de escala |
| [setScaleValue(double value)](#setScaleValue-double-) | Establece el valor de la escala |
| [getLocale()](#getLocale--) | Identificador de configuración regional |
| [setLocale(int value)](#setLocale-int-) | Establece el identificador de configuración regional |
### TextStyle() {#TextStyle--}
```
public TextStyle()
```


Constructor

### isBold() {#isBold--}
```
public final boolean isBold()
```


El texto está en negrita

**Returns:**
boolean - valor boolean
### setIsBold(boolean value) {#setIsBold-boolean-}
```
public final void setIsBold(boolean value)
```


Establece si el texto está en negrita

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de negrita |

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


El texto está en cursiva

**Returns:**
boolean - valor boolean
### setIsItalic(boolean value) {#setIsItalic-boolean-}
```
public final void setIsItalic(boolean value)
```


Establece si el texto está en cursiva

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de cursiva |

### getUnderlineType() {#getUnderlineType--}
```
public final byte getUnderlineType()
```


Tipo de subrayado para el texto

**Returns:**
byte - elemento UnderlineType
### setUnderlineType(byte value) {#setUnderlineType-byte-}
```
public final void setUnderlineType(byte value)
```


Establece el tipo de subrayado para el texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | Valor del tipo de subrayado |

### isOutline() {#isOutline--}
```
public final boolean isOutline()
```


El texto está contorneado

**Returns:**
boolean - valor boolean
### setIsOutline(boolean value) {#setIsOutline-boolean-}
```
public final void setIsOutline(boolean value)
```


Establece si el texto está contorneado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de contorno del texto |

### isShadow() {#isShadow--}
```
public final boolean isShadow()
```


El texto tiene sombra

**Returns:**
boolean - valor boolean
### setIsShadow(boolean value) {#setIsShadow-boolean-}
```
public final void setIsShadow(boolean value)
```


Establece si el texto tiene sombra

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de si el texto tiene sombra |

### isSmallCapsMode() {#isSmallCapsMode--}
```
public final boolean isSmallCapsMode()
```


Modo de versalitas habilitado

**Returns:**
boolean - valor boolean
### setIsSmallCapsMode(boolean value) {#setIsSmallCapsMode-boolean-}
```
public final void setIsSmallCapsMode(boolean value)
```


Activa/desactiva el modo de versalitas para el texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Modo de versalitas habilitado |

### isAllCapsMode() {#isAllCapsMode--}
```
public final boolean isAllCapsMode()
```


Modo de mayúsculas activado

**Returns:**
boolean - valor boolean
### setIsAllCapsMode(boolean value) {#setIsAllCapsMode-boolean-}
```
public final void setIsAllCapsMode(boolean value)
```


Activa/desactiva el modo de mayúsculas para el texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Modo de mayúsculas activado |

### isEmboss() {#isEmboss--}
```
public final boolean isEmboss()
```


El texto está en relieve

**Returns:**
boolean - valor boolean
### setIsEmboss(boolean value) {#setIsEmboss-boolean-}
```
public final void setIsEmboss(boolean value)
```


Establece si el texto está en relieve

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de si el texto está en relieve |

### isEngrave() {#isEngrave--}
```
public final boolean isEngrave()
```


El texto está grabado

**Returns:**
boolean - valor boolean
### setIsEngrave(boolean value) {#setIsEngrave-boolean-}
```
public final void setIsEngrave(boolean value)
```


Establece si el texto está grabado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Valor de si el texto está grabado |

### getRawTextSize() {#getRawTextSize--}
```
public final int getRawTextSize()
```


Tamaño del texto en métricas PUB (en EMU)

**Returns:**
int - valor int
### setRawTextSize(int value) {#setRawTextSize-int-}
```
public final void setRawTextSize(int value)
```


Establece el tamaño del texto en métricas PUB (en EMU)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Valor del tamaño del texto en EMUs |

### calculateTextSize() {#calculateTextSize--}
```
public final double calculateTextSize()
```


Calcula el tamaño del texto en puntos

**Returns:**
double - tamaño del texto en puntos
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Obtiene el índice del color en la matriz Document.Colors

**Returns:**
int - valor int
### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Establece el índice del color en la matriz Document.Colors

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Valor del índice de color |

### getFontIndex() {#getFontIndex--}
```
public final int getFontIndex()
```


Obtiene el índice del nombre de fuente en la matriz Document.FontNames

**Returns:**
int - valor int
### setFontIndex(int value) {#setFontIndex-int-}
```
public final void setFontIndex(int value)
```


Establece el índice del nombre de fuente en la matriz Document.FontNames

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Valor del índice de fuente |

### getSuperscriptType() {#getSuperscriptType--}
```
public final byte getSuperscriptType()
```


Tipo de superíndice

**Returns:**
byte - elemento SuperscriptType
### setSuperscriptType(byte value) {#setSuperscriptType-byte-}
```
public final void setSuperscriptType(byte value)
```


Establece el tipo de superíndice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | Valor del tipo de superíndice |

### getScaleValue() {#getScaleValue--}
```
public final double getScaleValue()
```


Valor de escala

**Returns:**
double - valor double
### setScaleValue(double value) {#setScaleValue-double-}
```
public final void setScaleValue(double value)
```


Establece el valor de la escala

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Valor de escala |

### getLocale() {#getLocale--}
```
public final int getLocale()
```


Identificador de configuración regional

**Returns:**
int - valor int
### setLocale(int value) {#setLocale-int-}
```
public final void setLocale(int value)
```


Establece el identificador de configuración regional

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Identificador de configuración regional |

