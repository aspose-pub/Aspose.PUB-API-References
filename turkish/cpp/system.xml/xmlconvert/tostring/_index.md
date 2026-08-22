---
title: "System::Xml::XmlConvert::ToString yöntemi"
linktitle: "ToString"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlConvert::ToString yöntemi. Boolean değerini C++'da bir String'e dönüştürür."
type: docs
weight: 2400
url: /tr/cpp/system.xml/xmlconvert/tostring/
---
## XmlConvert::ToString(bool) method


[Boolean](../../../system/boolean/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(bool value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | bool | Dönüştürülecek değer. |

### ReturnValue

[Boolean](../../../system/boolean/) değerinin, yani "true" veya "false" olan bir dize temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(char16_t) method


[Char](../../../system/char/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(char16_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | char16_t | Dönüştürülecek değer. |

### ReturnValue

[Char](../../../system/char/) değerinin dize temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(DateTime) method


[DateTime](../../../system/datetime/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(DateTime value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | DateTime | Dönüştürülecek değer. |

### ReturnValue

[DateTime](../../../system/datetime/) değerinin yyyy-MM-ddTHH:mm:ss biçiminde dize temsili, burada 'T' sabit bir karakterdir.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [DateTime](../../../system/datetime/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(DateTime, const String\&) method


[DateTime](../../../system/datetime/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(DateTime value, const String &format)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | DateTime | Dönüştürülecek değer. |
| biçim | const String\& | Dönüştürülen dizeyi nasıl görüntüleyeceğini tanımlayan format yapısı. Geçerli formatlar "yyyy-MM-ddTHH:mm:sszzzzzz" ve alt kümelerini içerir. |

### ReturnValue

Belirtilen formatta [DateTime](../../../system/datetime/) değerinin dize temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [DateTime](../../../system/datetime/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(DateTime, XmlDateTimeSerializationMode) method


Belirtilen XmlDateTimeSerializationMode kullanılarak [DateTime](../../../system/datetime/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(DateTime value, XmlDateTimeSerializationMode dateTimeOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | DateTime | Dönüştürülecek [DateTime](../../../system/datetime/) değeri. |
| dateTimeOption | XmlDateTimeSerializationMode | [DateTime](../../../system/datetime/) değerinin nasıl ele alınacağını belirten XmlDateTimeSerializationMode değerlerinden biri. |

### ReturnValue

[DateTime](../../../system/datetime/) değerinin bir [String](../../../system/string/) eşdeğeri.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [DateTime](../../../system/datetime/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(DateTimeOffset) method


Sağlanan [DateTimeOffset](../../../system/datetimeoffset/) değerini bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(DateTimeOffset value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | DateTimeOffset | Dönüştürülecek [DateTimeOffset](../../../system/datetimeoffset/) değeri. |

### ReturnValue

Sağlanan [DateTimeOffset](../../../system/datetimeoffset/) değerinin bir [String](../../../system/string/) temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(DateTimeOffset, const String\&) method


Sağlanan [DateTimeOffset](../../../system/datetimeoffset/) değerini belirtilen formatta bir [String](../../../system/string/) değerine dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(DateTimeOffset value, const String &format)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | DateTimeOffset | Dönüştürülecek [DateTimeOffset](../../../system/datetimeoffset/) değeri. |
| format | const String\& | **s**'nin dönüştürüldüğü format. format parametresi, XML dateTime türü için W3C Önerisi'nin herhangi bir alt kümesi olabilir. Daha fazla bilgi için XML [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) bölümüne ve [Schema](../../../system.xml.schema/) spesifikasyonuna bakın. |

### ReturnValue

Sağlanan [DateTimeOffset](../../../system/datetimeoffset/) öğesinin belirtilen formatta bir [String](../../../system/string/) temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [DateTimeOffset](../../../system/datetimeoffset/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(Decimal) method


[Decimal](../../../system/decimal/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(Decimal value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Decimal | Dönüştürülecek değer. |

### ReturnValue

[Decimal](../../../system/decimal/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [Decimal](../../../system/decimal/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(double) method


[Double](../../../system/double/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(double value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Dönüştürülecek değer. |

### ReturnValue

[Double](../../../system/double/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(float) method


[Single](../../../system/single/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(float value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Dönüştürülecek değer. |

### ReturnValue

[Single](../../../system/single/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(Guid) method


[Guid](../../../system/guid/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(Guid value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | Guid | Dönüştürülecek değer. |

### ReturnValue

[Guid](../../../system/guid/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(int16_t) method


[Int16](../../../system/int16/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(int16_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int16_t | Dönüştürülecek değer. |

### ReturnValue

[Int16](../../../system/int16/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(int32_t) method


[Int32](../../../system/int32/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(int32_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int32_t | Dönüştürülecek değer. |

### ReturnValue

[Int32](../../../system/int32/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(int64_t) method


[Int64](../../../system/int64/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(int64_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int64_t | Dönüştürülecek değer. |

### ReturnValue

[Int64](../../../system/int64/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(int8_t) method


[SByte](../../../system/sbyte/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(int8_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int8_t | Dönüştürülecek değer. |

### ReturnValue

[SByte](../../../system/sbyte/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(TimeSpan) method


[TimeSpan](../../../system/timespan/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(TimeSpan value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | TimeSpan | Dönüştürülecek değer. |

### ReturnValue

[TimeSpan](../../../system/timespan/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [TimeSpan](../../../system/timespan/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(uint16_t) method


[UInt16](../../../system/uint16/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(uint16_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | uint16_t | Dönüştürülecek değer. |

### ReturnValue

[UInt16](../../../system/uint16/) öğesinin bir string temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(uint32_t) method


[UInt32](../../../system/uint32/) öğesini bir [String](../../../system/string/)’e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(uint32_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | uint32_t | Dönüştürülecek değer. |

### ReturnValue

Bir [UInt32](../../../system/uint32/) dizesi temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(uint64_t) method


Bir [UInt64](../../../system/uint64/) değerini bir [String](../../../system/string/)e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(uint64_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | uint64_t | Dönüştürülecek değer. |

### ReturnValue

Bir [UInt64](../../../system/uint64/) dizesi temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToString(uint8_t) method


Bir [Byte](../../../system/byte/) değerini bir [String](../../../system/string/)e dönüştürür.

```cpp
static String System::Xml::XmlConvert::ToString(uint8_t value)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | uint8_t | Dönüştürülecek değer. |

### ReturnValue

Bir [Byte](../../../system/byte/) dizesi temsili.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
