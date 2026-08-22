---
title: "TextStyle"
second_title: "مرجع API لـ Aspose.PUB لـ Java"
description: "يصف نمط نص PUB"
type: docs
weight: 23
url: /ar/java/com.aspose.pub/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.pub.BaseStyle](../../com.aspose.pub/basestyle)
```
public class TextStyle extends BaseStyle
```

يصف نمط نص PUB
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextStyle()](#TextStyle--) | المنشئ |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isBold()](#isBold--) | هل النص غامق |
| [setIsBold(boolean value)](#setIsBold-boolean-) | يضبط ما إذا كان النص غامقًا |
| [isItalic()](#isItalic--) | هل النص مائل |
| [setIsItalic(boolean value)](#setIsItalic-boolean-) | يضبط ما إذا كان النص مائلًا |
| [getUnderlineType()](#getUnderlineType--) | نوع التسطير للنص |
| [setUnderlineType(byte value)](#setUnderlineType-byte-) | يضبط نوع التسطير للنص |
| [isOutline()](#isOutline--) | هل النص محدد بالحد |
| [setIsOutline(boolean value)](#setIsOutline-boolean-) | يضبط ما إذا كان النص محددًا بالحد |
| [isShadow()](#isShadow--) | هل النص مظلَل |
| [setIsShadow(boolean value)](#setIsShadow-boolean-) | يضبط ما إذا كان النص مظلَلًا |
| [isSmallCapsMode()](#isSmallCapsMode--) | هل تم تمكين وضع الحروف الصغيرة الكبيرة |
| [setIsSmallCapsMode(boolean value)](#setIsSmallCapsMode-boolean-) | يفعل/يعطل وضع الحروف الصغيرة للنص |
| [isAllCapsMode()](#isAllCapsMode--) | هل تم تمكين وضع الأحرف الكبيرة بالكامل |
| [setIsAllCapsMode(boolean value)](#setIsAllCapsMode-boolean-) | يفعل/يعطل وضع الحروف الكبيرة للنص |
| [isEmboss()](#isEmboss--) | هل النص بارز |
| [setIsEmboss(boolean value)](#setIsEmboss-boolean-) | يضبط ما إذا كان النص بارزًا |
| [isEngrave()](#isEngrave--) | هل النص محفور |
| [setIsEngrave(boolean value)](#setIsEngrave-boolean-) | يضبط ما إذا كان النص محفورًا |
| [getRawTextSize()](#getRawTextSize--) | حجم النص في مقاييس PUB (بوحدات EMU). |
| [setRawTextSize(int value)](#setRawTextSize-int-) | يضبط حجم النص في مقاييس PUB (بوحدات EMU). |
| [calculateTextSize()](#calculateTextSize--) | يحسب حجم النص بالنقاط |
| [getColorIndex()](#getColorIndex--) | يحصل على فهرس اللون في مصفوفة Document.Colors |
| [setColorIndex(int value)](#setColorIndex-int-) | يضبط فهرس اللون في مصفوفة Document.Colors |
| [getFontIndex()](#getFontIndex--) | يحصل على فهرس اسم الخط في مصفوفة Document.FontNames |
| [setFontIndex(int value)](#setFontIndex-int-) | يضبط فهرس اسم الخط في مصفوفة Document.FontNames |
| [getSuperscriptType()](#getSuperscriptType--) | نوع النص العلوي |
| [setSuperscriptType(byte value)](#setSuperscriptType-byte-) | يضبط نوع النص العلوي |
| [getScaleValue()](#getScaleValue--) | قيمة المقياس |
| [setScaleValue(double value)](#setScaleValue-double-) | يضبط قيمة المقياس |
| [getLocale()](#getLocale--) | معرف اللغة |
| [setLocale(int value)](#setLocale-int-) | يضبط معرف اللغة |
### TextStyle() {#TextStyle--}
```
public TextStyle()
```


المنشئ

### isBold() {#isBold--}
```
public final boolean isBold()
```


هل النص غامق

**Returns:**
boolean - قيمة boolean
### setIsBold(boolean value) {#setIsBold-boolean-}
```
public final void setIsBold(boolean value)
```


يضبط ما إذا كان النص غامقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة الغامق |

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


هل النص مائل

**Returns:**
boolean - قيمة boolean
### setIsItalic(boolean value) {#setIsItalic-boolean-}
```
public final void setIsItalic(boolean value)
```


يضبط ما إذا كان النص مائلًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة المائل |

### getUnderlineType() {#getUnderlineType--}
```
public final byte getUnderlineType()
```


نوع التسطير للنص

**Returns:**
بايت - عنصر UnderlineType
### setUnderlineType(byte value) {#setUnderlineType-byte-}
```
public final void setUnderlineType(byte value)
```


يضبط نوع التسطير للنص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | بايت | قيمة نوع التسطير |

### isOutline() {#isOutline--}
```
public final boolean isOutline()
```


هل النص محدد بالحد

**Returns:**
boolean - قيمة boolean
### setIsOutline(boolean value) {#setIsOutline-boolean-}
```
public final void setIsOutline(boolean value)
```


يضبط ما إذا كان النص محددًا بالحد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة تخطيط النص |

### isShadow() {#isShadow--}
```
public final boolean isShadow()
```


هل النص مظلَل

**Returns:**
boolean - قيمة boolean
### setIsShadow(boolean value) {#setIsShadow-boolean-}
```
public final void setIsShadow(boolean value)
```


يضبط ما إذا كان النص مظلَلًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة ما إذا كان النص مظلل |

### isSmallCapsMode() {#isSmallCapsMode--}
```
public final boolean isSmallCapsMode()
```


هل تم تمكين وضع الحروف الصغيرة الكبيرة

**Returns:**
boolean - قيمة boolean
### setIsSmallCapsMode(boolean value) {#setIsSmallCapsMode-boolean-}
```
public final void setIsSmallCapsMode(boolean value)
```


يفعل/يعطل وضع الحروف الصغيرة للنص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | هل تم تمكين وضع الحروف الصغيرة الكبيرة |

### isAllCapsMode() {#isAllCapsMode--}
```
public final boolean isAllCapsMode()
```


هل تم تمكين وضع الأحرف الكبيرة بالكامل

**Returns:**
boolean - قيمة boolean
### setIsAllCapsMode(boolean value) {#setIsAllCapsMode-boolean-}
```
public final void setIsAllCapsMode(boolean value)
```


يفعل/يعطل وضع الحروف الكبيرة للنص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | هل تم تمكين وضع الأحرف الكبيرة بالكامل |

### isEmboss() {#isEmboss--}
```
public final boolean isEmboss()
```


هل النص بارز

**Returns:**
boolean - قيمة boolean
### setIsEmboss(boolean value) {#setIsEmboss-boolean-}
```
public final void setIsEmboss(boolean value)
```


يضبط ما إذا كان النص بارزًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة النص المنقوش |

### isEngrave() {#isEngrave--}
```
public final boolean isEngrave()
```


هل النص محفور

**Returns:**
boolean - قيمة boolean
### setIsEngrave(boolean value) {#setIsEngrave-boolean-}
```
public final void setIsEngrave(boolean value)
```


يضبط ما إذا كان النص محفورًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي | قيمة ما إذا كان النص محفورًا |

### getRawTextSize() {#getRawTextSize--}
```
public final int getRawTextSize()
```


حجم النص في مقاييس PUB (بوحدات EMU).

**Returns:**
int - قيمة int
### setRawTextSize(int value) {#setRawTextSize-int-}
```
public final void setRawTextSize(int value)
```


يضبط حجم النص في مقاييس PUB (بوحدات EMU).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | قيمة حجم النص بوحدات EMU |

### calculateTextSize() {#calculateTextSize--}
```
public final double calculateTextSize()
```


يحسب حجم النص بالنقاط

**Returns:**
مزدوج - حجم النص بالنقاط
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


يحصل على فهرس اللون في مصفوفة Document.Colors

**Returns:**
int - قيمة int
### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


يضبط فهرس اللون في مصفوفة Document.Colors

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | قيمة فهرس اللون |

### getFontIndex() {#getFontIndex--}
```
public final int getFontIndex()
```


يحصل على فهرس اسم الخط في مصفوفة Document.FontNames

**Returns:**
int - قيمة int
### setFontIndex(int value) {#setFontIndex-int-}
```
public final void setFontIndex(int value)
```


يضبط فهرس اسم الخط في مصفوفة Document.FontNames

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | قيمة فهرس الخط |

### getSuperscriptType() {#getSuperscriptType--}
```
public final byte getSuperscriptType()
```


نوع النص العلوي

**Returns:**
بايت - عنصر SuperscriptType
### setSuperscriptType(byte value) {#setSuperscriptType-byte-}
```
public final void setSuperscriptType(byte value)
```


يضبط نوع النص العلوي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | بايت | قيمة نوع النص العلوي |

### getScaleValue() {#getScaleValue--}
```
public final double getScaleValue()
```


قيمة المقياس

**Returns:**
مزدوج - قيمة مزدوجة
### setScaleValue(double value) {#setScaleValue-double-}
```
public final void setScaleValue(double value)
```


يضبط قيمة المقياس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | قيمة المقياس |

### getLocale() {#getLocale--}
```
public final int getLocale()
```


معرف اللغة

**Returns:**
int - قيمة int
### setLocale(int value) {#setLocale-int-}
```
public final void setLocale(int value)
```


يضبط معرف اللغة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | معرف اللغة |

