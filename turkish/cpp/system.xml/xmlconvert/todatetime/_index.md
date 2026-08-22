---
title: "System::Xml::XmlConvert::ToDateTime metodu"
linktitle: "ToDateTime"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlConvert::ToDateTime metodu. String'i C++'da bir DateTime eşdeğerine dönüştürür."
type: docs
weight: 1400
url: /tr/cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Bir [String](../../../system/string/) değerini bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek dize. |

### ReturnValue

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## Ayrıca Bakınız

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Bir [String](../../../system/string/) değerini bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek dize. |
| formats | const ArrayPtr\<String\>\& | Dönüştürülen [DateTime](../../../system/datetime/) üzerine uygulanacak format yapılarını içeren bir dizi. Geçerli formatlar "yyyy-MM-ddTHH:mm:sszzzzzz" ve alt kümelerini içerir. |

### ReturnValue

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## Ayrıca Bakınız

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Bir [String](../../../system/string/) değerini bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek dize. |
| format | const String\& | Dönüştürülen [DateTime](../../../system/datetime/) üzerine uygulanacak format yapısı. Geçerli formatlar "yyyy-MM-ddTHH:mm:sszzzzzz" ve alt kümelerini içerir. Dize bu formata göre doğrulanır. |

### ReturnValue

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## Ayrıca Bakınız

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Belirtilen XmlDateTimeSerializationMode kullanarak [String](../../../system/string/) değerini bir [DateTime](../../../system/datetime/)e dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const String\& | Dönüştürülecek [String](../../../system/string/) değeri. |
| dateTimeOption | XmlDateTimeSerializationMode | Tarih bir UTC tarihi ise yerel saate dönüştürülüp dönüştürülmeyeceğini veya Koordinatlı Evrensel Zaman (UTC) olarak korunacağını belirten enum değerlerinden biri. |

### ReturnValue

Bir [String](../../../system/string/) değerinin [DateTime](../../../system/datetime/) eşdeğeri.

## Ayrıca Bakınız

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
