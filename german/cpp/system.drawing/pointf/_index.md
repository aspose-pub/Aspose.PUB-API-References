---
title: "System::Drawing::PointF-Klasse"
linktitle: "PointF"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::PointF-Klasse. Stellt ein Paar von Gleitkomma‑Koordinaten X und Y mit einfacher Genauigkeit dar, die einen Punkt in einer zweidimensionalen Ebene beschreiben. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr‑Klasse, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 1800
url: /de/cpp/system.drawing/pointf/
---
## PointF class


Stellt ein Paar von Gleitkomma‑Koordinaten X und Y mit einfacher Genauigkeit dar, die einen Punkt in einer zweidimensionalen Ebene beschreiben. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/)-Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class PointF
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Add](./add/)(const PointF\&, const SizeF\&) | Addiert die Breiten- und Höhenwerte des angegebenen [SizeF](../sizef/) Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts entsprechend. |
| static [Add](./add/)(const PointF\&, const Size\&) | Addiert die Breiten- und Höhenwerte des angegebenen [Size](../size/) Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts entsprechend. |
| [Equals](./equals/)(const PointF\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene Objekt gleich sind, d. h. dass sie dasselbe Paar von X- und Y-Koordinatenwerten darstellen. |
| [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob sowohl X- als auch Y-Koordinatenwerte gleich 0 sind. |
| [get_X](./get_x/)() const | Gibt den Wert der X-Koordinate zurück, der vom aktuellen Objekt dargestellt wird. |
| [get_Y](./get_y/)() const | Gibt den Wert der Y-Koordinate zurück, der vom aktuellen Objekt dargestellt wird. |
| [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| [IsNull](./isnull/)() const | Gibt immer false zurück. |
| explicit [operator bool](./operatorbool/)() | Gibt immer true zurück. |
| [PointF](./pointf/)() | Erstellt ein neues [PointF](./)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit 0. |
| [PointF](./pointf/)(float, float) | Erstellt ein neues [PointF](./)-Objekt und initialisiert es mit den angegebenen Werten. |
| [PointF](./pointf/)(const SizeF\&) | Erstellt ein neues [PointF](./)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit den Breiten- und Höhenwerten des angegebenen [SizeF](../sizef/)-Objekts entsprechend. |
| [set_X](./set_x/)(float) | Setzt den Wert der X-Koordinate, die vom aktuellen Objekt dargestellt wird. |
| [set_Y](./set_y/)(float) | Setzt den Wert der Y-Koordinate, die vom aktuellen Objekt dargestellt wird. |
| static [Subtract](./subtract/)(const PointF\&, const SizeF\&) | Subtrahiert die Breiten- und Höhenwerte des angegebenen [SizeF](../sizef/) Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts entsprechend. |
| static [Subtract](./subtract/)(const PointF\&, const Size\&) | Subtrahiert die Breiten- und Höhenwerte des angegebenen [Size](../size/) Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts entsprechend. |
| [ToString](./tostring/)() const | Gibt die String-Darstellung des Paares von X- und Y-Koordinatenwerten zurück, die vom aktuellen Objekt dargestellt werden. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Eine leere Instanz der Klasse [PointF](./), deren X- und Y-Koordinatenwerte 0 sind. |
## Siehe auch

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
