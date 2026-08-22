---
title: "TextStyle"
second_title: "Aspose.PUB for Java API-Referenz"
description: "Beschreibt den PUB-Textstil"
type: docs
weight: 23
url: /de/java/com.aspose.pub/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.pub.BaseStyle](../../com.aspose.pub/basestyle)
```
public class TextStyle extends BaseStyle
```

Beschreibt den PUB-Textstil
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextStyle()](#TextStyle--) | Konstruktor |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isBold()](#isBold--) | Ist der Text fett |
| [setIsBold(boolean value)](#setIsBold-boolean-) | Setzt, ob der Text fett ist |
| [isItalic()](#isItalic--) | Ist der Text kursiv |
| [setIsItalic(boolean value)](#setIsItalic-boolean-) | Setzt, ob der Text kursiv ist |
| [getUnderlineType()](#getUnderlineType--) | Unterstreichungsart für Text |
| [setUnderlineType(byte value)](#setUnderlineType-byte-) | Setzt die Unterstreichungsart für Text |
| [isOutline()](#isOutline--) | Ist der Text umrandet |
| [setIsOutline(boolean value)](#setIsOutline-boolean-) | Setzt, ob der Text umrandet ist |
| [isShadow()](#isShadow--) | Ist der Text schattiert |
| [setIsShadow(boolean value)](#setIsShadow-boolean-) | Setzt, ob der Text schattiert ist |
| [isSmallCapsMode()](#isSmallCapsMode--) | Ist der Kapitälchenmodus aktiviert |
| [setIsSmallCapsMode(boolean value)](#setIsSmallCapsMode-boolean-) | Aktiviert/deaktiviert Kapitälchenmodus für Text |
| [isAllCapsMode()](#isAllCapsMode--) | Ist Großbuchstabenmodus aktiviert |
| [setIsAllCapsMode(boolean value)](#setIsAllCapsMode-boolean-) | Aktiviert/deaktiviert Großbuchstabenmodus für Text |
| [isEmboss()](#isEmboss--) | Ist Text erhaben |
| [setIsEmboss(boolean value)](#setIsEmboss-boolean-) | Setzt, ob Text erhaben ist |
| [isEngrave()](#isEngrave--) | Ist Text graviert |
| [setIsEngrave(boolean value)](#setIsEngrave-boolean-) | Setzt, ob Text graviert ist |
| [getRawTextSize()](#getRawTextSize--) | Größe des Textes in PUB-Metriken (in EMUs) |
| [setRawTextSize(int value)](#setRawTextSize-int-) | Setzt Größe des Textes in PUB-Metriken (in EMUs) |
| [calculateTextSize()](#calculateTextSize--) | Berechnet Textgröße in Punkten |
| [getColorIndex()](#getColorIndex--) | Ermittelt Index der Farbe im Document.Colors-Array |
| [setColorIndex(int value)](#setColorIndex-int-) | Setzt Index der Farbe im Document.Colors-Array |
| [getFontIndex()](#getFontIndex--) | Ermittelt Index des Schriftartnamens im Document.FontNames-Array |
| [setFontIndex(int value)](#setFontIndex-int-) | Setzt Index des Schriftartnamens im Document.FontNames-Array |
| [getSuperscriptType()](#getSuperscriptType--) | Typ des Hochgestellten |
| [setSuperscriptType(byte value)](#setSuperscriptType-byte-) | Setzt Typ des Hochscripts |
| [getScaleValue()](#getScaleValue--) | Wert der Skalierung |
| [setScaleValue(double value)](#setScaleValue-double-) | Setzt Wert der Skalierung |
| [getLocale()](#getLocale--) | Gebietsschema-Bezeichner |
| [setLocale(int value)](#setLocale-int-) | Setzt Gebietsschema-Identifikator |
### TextStyle() {#TextStyle--}
```
public TextStyle()
```


Konstruktor

### isBold() {#isBold--}
```
public final boolean isBold()
```


Ist der Text fett

**Returns:**
boolean - boolean-Wert
### setIsBold(boolean value) {#setIsBold-boolean-}
```
public final void setIsBold(boolean value)
```


Setzt, ob der Text fett ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Fettwert |

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


Ist der Text kursiv

**Returns:**
boolean - boolean-Wert
### setIsItalic(boolean value) {#setIsItalic-boolean-}
```
public final void setIsItalic(boolean value)
```


Setzt, ob der Text kursiv ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Kursivwert |

### getUnderlineType() {#getUnderlineType--}
```
public final byte getUnderlineType()
```


Unterstreichungsart für Text

**Returns:**
Byte - UnderlineType-Element
### setUnderlineType(byte value) {#setUnderlineType-byte-}
```
public final void setUnderlineType(byte value)
```


Setzt die Unterstreichungsart für Text

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Wert des Unterstreichungstyps |

### isOutline() {#isOutline--}
```
public final boolean isOutline()
```


Ist der Text umrandet

**Returns:**
boolean - boolean-Wert
### setIsOutline(boolean value) {#setIsOutline-boolean-}
```
public final void setIsOutline(boolean value)
```


Setzt, ob der Text umrandet ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Textumrisswert |

### isShadow() {#isShadow--}
```
public final boolean isShadow()
```


Ist der Text schattiert

**Returns:**
boolean - boolean-Wert
### setIsShadow(boolean value) {#setIsShadow-boolean-}
```
public final void setIsShadow(boolean value)
```


Setzt, ob der Text schattiert ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Textschattenwert |

### isSmallCapsMode() {#isSmallCapsMode--}
```
public final boolean isSmallCapsMode()
```


Ist der Kapitälchenmodus aktiviert

**Returns:**
boolean - boolean-Wert
### setIsSmallCapsMode(boolean value) {#setIsSmallCapsMode-boolean-}
```
public final void setIsSmallCapsMode(boolean value)
```


Aktiviert/deaktiviert Kapitälchenmodus für Text

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist der Kapitälchenmodus aktiviert |

### isAllCapsMode() {#isAllCapsMode--}
```
public final boolean isAllCapsMode()
```


Ist Großbuchstabenmodus aktiviert

**Returns:**
boolean - boolean-Wert
### setIsAllCapsMode(boolean value) {#setIsAllCapsMode-boolean-}
```
public final void setIsAllCapsMode(boolean value)
```


Aktiviert/deaktiviert Großbuchstabenmodus für Text

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Großbuchstabenmodus aktiviert |

### isEmboss() {#isEmboss--}
```
public final boolean isEmboss()
```


Ist Text erhaben

**Returns:**
boolean - boolean-Wert
### setIsEmboss(boolean value) {#setIsEmboss-boolean-}
```
public final void setIsEmboss(boolean value)
```


Setzt, ob Text erhaben ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Textprägewert |

### isEngrave() {#isEngrave--}
```
public final boolean isEngrave()
```


Ist Text graviert

**Returns:**
boolean - boolean-Wert
### setIsEngrave(boolean value) {#setIsEngrave-boolean-}
```
public final void setIsEngrave(boolean value)
```


Setzt, ob Text graviert ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Ist Textgravurwert |

### getRawTextSize() {#getRawTextSize--}
```
public final int getRawTextSize()
```


Größe des Textes in PUB-Metriken (in EMUs)

**Returns:**
int - int-Wert
### setRawTextSize(int value) {#setRawTextSize-int-}
```
public final void setRawTextSize(int value)
```


Setzt Größe des Textes in PUB-Metriken (in EMUs)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Wert der Textgröße in EMUs |

### calculateTextSize() {#calculateTextSize--}
```
public final double calculateTextSize()
```


Berechnet Textgröße in Punkten

**Returns:**
double - Textgröße in Punkten
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Ermittelt Index der Farbe im Document.Colors-Array

**Returns:**
int - int-Wert
### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Setzt Index der Farbe im Document.Colors-Array

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Wert des Farbindex |

### getFontIndex() {#getFontIndex--}
```
public final int getFontIndex()
```


Ermittelt Index des Schriftartnamens im Document.FontNames-Array

**Returns:**
int - int-Wert
### setFontIndex(int value) {#setFontIndex-int-}
```
public final void setFontIndex(int value)
```


Setzt Index des Schriftartnamens im Document.FontNames-Array

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Wert des Schriftartindex |

### getSuperscriptType() {#getSuperscriptType--}
```
public final byte getSuperscriptType()
```


Typ des Hochgestellten

**Returns:**
byte - SuperscriptType-Element
### setSuperscriptType(byte value) {#setSuperscriptType-byte-}
```
public final void setSuperscriptType(byte value)
```


Setzt Typ des Hochscripts

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Wert des Hochstellungstyps |

### getScaleValue() {#getScaleValue--}
```
public final double getScaleValue()
```


Wert der Skalierung

**Returns:**
double - Doppelwert
### setScaleValue(double value) {#setScaleValue-double-}
```
public final void setScaleValue(double value)
```


Setzt Wert der Skalierung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Wert der Skalierung |

### getLocale() {#getLocale--}
```
public final int getLocale()
```


Gebietsschema-Bezeichner

**Returns:**
int - int-Wert
### setLocale(int value) {#setLocale-int-}
```
public final void setLocale(int value)
```


Setzt Gebietsschema-Identifikator

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Gebietsschema-Bezeichner |

