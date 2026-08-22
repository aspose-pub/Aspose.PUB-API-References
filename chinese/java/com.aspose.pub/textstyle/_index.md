---
title: "TextStyle"
second_title: "Aspose.PUB for Java API 参考"
description: "描述 PUB 文本样式"
type: docs
weight: 23
url: /zh/java/com.aspose.pub/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.pub.BaseStyle](../../com.aspose.pub/basestyle)
```
public class TextStyle extends BaseStyle
```

描述 PUB 文本样式
## 构造函数

| Constructor | 描述 |
| --- | --- |
| [TextStyle()](#TextStyle--) | Constructor |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isBold()](#isBold--) | 文本是否加粗 |
| [setIsBold(boolean value)](#setIsBold-boolean-) | 设置文本加粗 |
| [isItalic()](#isItalic--) | 文本是否斜体 |
| [setIsItalic(boolean value)](#setIsItalic-boolean-) | 设置文本斜体 |
| [getUnderlineType()](#getUnderlineType--) | 文本的下划线类型 |
| [setUnderlineType(byte value)](#setUnderlineType-byte-) | 设置文本的下划线类型 |
| [isOutline()](#isOutline--) | 文本是否描边 |
| [setIsOutline(boolean value)](#setIsOutline-boolean-) | 设置文本描边 |
| [isShadow()](#isShadow--) | 文本是否有阴影 |
| [setIsShadow(boolean value)](#setIsShadow-boolean-) | 设置文本阴影 |
| [isSmallCapsMode()](#isSmallCapsMode--) | 小型大写模式是否已启用 |
| [setIsSmallCapsMode(boolean value)](#setIsSmallCapsMode-boolean-) | 启用/禁用文本的小型大写模式 |
| [isAllCapsMode()](#isAllCapsMode--) | 是否已启用全大写模式 |
| [setIsAllCapsMode(boolean value)](#setIsAllCapsMode-boolean-) | 启用/禁用文本的全大写模式 |
| [isEmboss()](#isEmboss--) | 文本是否压纹 |
| [setIsEmboss(boolean value)](#setIsEmboss-boolean-) | 设置文本压纹 |
| [isEngrave()](#isEngrave--) | 文本是否雕刻 |
| [setIsEngrave(boolean value)](#setIsEngrave-boolean-) | 设置文本雕刻 |
| [getRawTextSize()](#getRawTextSize--) | PUB 指标中的文本大小（以 EMU 为单位） |
| [setRawTextSize(int value)](#setRawTextSize-int-) | 设置 PUB 指标中的文本大小（以 EMU 为单位） |
| [calculateTextSize()](#calculateTextSize--) | 计算文本的点大小 |
| [getColorIndex()](#getColorIndex--) | 获取 Document.Colors 数组中颜色的索引 |
| [setColorIndex(int value)](#setColorIndex-int-) | 设置 Document.Colors 数组中颜色的索引 |
| [getFontIndex()](#getFontIndex--) | 获取 Document.FontNames 数组中字体名称的索引 |
| [setFontIndex(int value)](#setFontIndex-int-) | 设置 Document.FontNames 数组中字体名称的索引 |
| [getSuperscriptType()](#getSuperscriptType--) | 上标类型 |
| [setSuperscriptType(byte value)](#setSuperscriptType-byte-) | 设置上标的类型 |
| [getScaleValue()](#getScaleValue--) | 比例值 |
| [setScaleValue(double value)](#setScaleValue-double-) | 设置比例的值 |
| [getLocale()](#getLocale--) | 区域标识符 |
| [setLocale(int value)](#setLocale-int-) | 设置区域标识符 |
### TextStyle() {#TextStyle--}
```
public TextStyle()
```


Constructor

### isBold() {#isBold--}
```
public final boolean isBold()
```


文本是否加粗

**Returns:**
boolean - boolean 值
### setIsBold(boolean value) {#setIsBold-boolean-}
```
public final void setIsBold(boolean value)
```


设置文本加粗

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 是否加粗的值 |

### isItalic() {#isItalic--}
```
public final boolean isItalic()
```


文本是否斜体

**Returns:**
boolean - boolean 值
### setIsItalic(boolean value) {#setIsItalic-boolean-}
```
public final void setIsItalic(boolean value)
```


设置文本斜体

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 是否斜体的值 |

### getUnderlineType() {#getUnderlineType--}
```
public final byte getUnderlineType()
```


文本的下划线类型

**Returns:**
字节 - UnderlineType 元素
### setUnderlineType(byte value) {#setUnderlineType-byte-}
```
public final void setUnderlineType(byte value)
```


设置文本的下划线类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 字节 | 下划线类型的值 |

### isOutline() {#isOutline--}
```
public final boolean isOutline()
```


文本是否描边

**Returns:**
boolean - boolean 值
### setIsOutline(boolean value) {#setIsOutline-boolean-}
```
public final void setIsOutline(boolean value)
```


设置文本描边

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 文本是否为轮廓的值 |

### isShadow() {#isShadow--}
```
public final boolean isShadow()
```


文本是否有阴影

**Returns:**
boolean - boolean 值
### setIsShadow(boolean value) {#setIsShadow-boolean-}
```
public final void setIsShadow(boolean value)
```


设置文本阴影

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 文本是否有阴影的值 |

### isSmallCapsMode() {#isSmallCapsMode--}
```
public final boolean isSmallCapsMode()
```


小型大写模式是否已启用

**Returns:**
boolean - boolean 值
### setIsSmallCapsMode(boolean value) {#setIsSmallCapsMode-boolean-}
```
public final void setIsSmallCapsMode(boolean value)
```


启用/禁用文本的小型大写模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 小型大写模式是否已启用 |

### isAllCapsMode() {#isAllCapsMode--}
```
public final boolean isAllCapsMode()
```


是否已启用全大写模式

**Returns:**
boolean - boolean 值
### setIsAllCapsMode(boolean value) {#setIsAllCapsMode-boolean-}
```
public final void setIsAllCapsMode(boolean value)
```


启用/禁用文本的全大写模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 是否已启用全大写模式 |

### isEmboss() {#isEmboss--}
```
public final boolean isEmboss()
```


文本是否压纹

**Returns:**
boolean - boolean 值
### setIsEmboss(boolean value) {#setIsEmboss-boolean-}
```
public final void setIsEmboss(boolean value)
```


设置文本压纹

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 文本是否浮雕的值 |

### isEngrave() {#isEngrave--}
```
public final boolean isEngrave()
```


文本是否雕刻

**Returns:**
boolean - boolean 值
### setIsEngrave(boolean value) {#setIsEngrave-boolean-}
```
public final void setIsEngrave(boolean value)
```


设置文本雕刻

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 布尔 | 文本是否为雕刻的值 |

### getRawTextSize() {#getRawTextSize--}
```
public final int getRawTextSize()
```


PUB 指标中的文本大小（以 EMU 为单位）

**Returns:**
int - int 值
### setRawTextSize(int value) {#setRawTextSize-int-}
```
public final void setRawTextSize(int value)
```


设置 PUB 指标中的文本大小（以 EMU 为单位）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 文本大小（EMU）的值 |

### calculateTextSize() {#calculateTextSize--}
```
public final double calculateTextSize()
```


计算文本的点大小

**Returns:**
双精度 - 文本大小（点）
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


获取 Document.Colors 数组中颜色的索引

**Returns:**
int - int 值
### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


设置 Document.Colors 数组中颜色的索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 颜色索引的值 |

### getFontIndex() {#getFontIndex--}
```
public final int getFontIndex()
```


获取 Document.FontNames 数组中字体名称的索引

**Returns:**
int - int 值
### setFontIndex(int value) {#setFontIndex-int-}
```
public final void setFontIndex(int value)
```


设置 Document.FontNames 数组中字体名称的索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 字体索引的值 |

### getSuperscriptType() {#getSuperscriptType--}
```
public final byte getSuperscriptType()
```


上标类型

**Returns:**
字节 - SuperscriptType 元素
### setSuperscriptType(byte value) {#setSuperscriptType-byte-}
```
public final void setSuperscriptType(byte value)
```


设置上标的类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | 字节 | 上标类型的值 |

### getScaleValue() {#getScaleValue--}
```
public final double getScaleValue()
```


比例值

**Returns:**
双精度 - 双精度值
### setScaleValue(double value) {#setScaleValue-double-}
```
public final void setScaleValue(double value)
```


设置比例的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 比例值 |

### getLocale() {#getLocale--}
```
public final int getLocale()
```


区域标识符

**Returns:**
int - int 值
### setLocale(int value) {#setLocale-int-}
```
public final void setLocale(int value)
```


设置区域标识符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 区域标识符 |

