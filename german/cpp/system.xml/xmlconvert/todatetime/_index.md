---
title: "System::Xml::XmlConvert::ToDateTime Methode"
linktitle: "ToDateTime"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlConvert::ToDateTime Methode. Konvertiert den String zu einem DateTime-Äquivalent in C++."
type: docs
weight: 1400
url: /de/cpp/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) method


Konvertiert den [String](../../../system/string/) zu einem [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const String\& | Der zu konvertierende String. |

### ReturnValue

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## Siehe auch

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) method


Konvertiert den [String](../../../system/string/) zu einem [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const String\& | Der zu konvertierende String. |
| formats | const ArrayPtr\<String\>\& | Ein Array, das die Formatstrukturen enthält, die auf das konvertierte [DateTime](../../../system/datetime/) angewendet werden sollen. Gültige Formate umfassen "yyyy-MM-ddTHH:mm:sszzzzzz" und dessen Teilmengen. |

### ReturnValue

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## Siehe auch

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, const String\&) method


Konvertiert den [String](../../../system/string/) zu einem [DateTime](../../../system/datetime/) Äquivalent.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const String\& | Der zu konvertierende String. |
| format | const String\& | Die Formatstruktur, die auf das konvertierte [DateTime](../../../system/datetime/) angewendet werden soll. Gültige Formate umfassen "yyyy-MM-ddTHH:mm:sszzzzzz" und dessen Teilmengen. Die Zeichenkette wird anhand dieses Formats validiert. |

### ReturnValue

Ein [DateTime](../../../system/datetime/) Äquivalent der Zeichenkette.

## Siehe auch

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) method


Konvertiert den [String](../../../system/string/) zu einem [DateTime](../../../system/datetime/) unter Verwendung des angegebenen XmlDateTimeSerializationMode.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const String\& | Der [String](../../../system/string/) Wert, der konvertiert werden soll. |
| dateTimeOption | XmlDateTimeSerializationMode | Einer der Aufzählungswerte, die angeben, ob das Datum in die lokale Zeit konvertiert oder als koordinierte Weltzeit (UTC) beibehalten werden soll, falls es ein UTC-Datum ist. |

### ReturnValue

Ein [DateTime](../../../system/datetime/) Äquivalent des [String](../../../system/string/).

## Siehe auch

* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
