---
title: "Klasse System::Version"
linktitle: "Version"
second_title: "Aspose.PUB für C++"
description: "Klasse System::Version. Stellt eine Versionsnummer dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 7000
url: /de/cpp/system/version/
---
## Version class


Stellt eine Versionsnummer dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
class Version
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CompareTo](./compareto/)(const Version\&) const | Vergleicht die von dem aktuellen Objekt und dem angegebenen Objekt dargestellten Versionen. |
| [Equals](./equals/)(const Version\&) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten Versionsnummern gleich sind. |
| [get_Build](./get_build/)() const | Gibt die Build-Nummer zurück. |
| [get_Major](./get_major/)() const | Gibt die Hauptversion zurück. |
| [get_MajorRevision](./get_majorrevision/)() const | Gibt den hohen 16-Bit-Wert der Revisionsnummer zurück. |
| [get_Minor](./get_minor/)() const | Gibt die Nebenversionsnummer zurück. |
| [get_MinorRevision](./get_minorrevision/)() const | Gibt den niedrigen 16-Bit-Wert der Revisionsnummer zurück. |
| [get_Revision](./get_revision/)() const | Gibt die Revisionsnummer zurück. |
| [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| static [Parse](./parse/)(const String\&) | Konvertiert die String-Darstellung einer Versionsnummer in eine äquivalente Instanz der Klasse [Version](./). |
| [ToString](./tostring/)() const | Gibt die String-Darstellung der vom aktuellen Objekt dargestellten Versionsnummer zurück. |
| [ToString](./tostring/)(int) const | Gibt die String-Darstellung der angegebenen Anzahl von Abschnitten der vom aktuellen Objekt dargestellten Versionsnummer zurück. |
| [Version](./version/)(int, int, int, int) | Konstruiert eine Instanz, die die angegebenen Haupt-, Neben-, Build- und Revisionswerte darstellt. |
| [Version](./version/)(int, int, int) | Konstruiert eine Instanz, die die angegebenen Haupt-, Neben- und Build-Werte darstellt. |
| [Version](./version/)(int, int) | Konstruiert eine Instanz, die die angegebenen Haupt- und Werte darstellt. |
| [Version](./version/)(const String\&) | Konstruiert eine Instanz, die die als String dargestellte Versionsnummer repräsentiert. |
| [Version](./version/)() | Konstruiert eine Instanz, die die Versionsnummer 0.0.-1.-1 darstellt. |
## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
