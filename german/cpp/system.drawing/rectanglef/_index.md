---
title: "System::Drawing::RectangleF Klasse"
linktitle: "RectangleF"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::RectangleF Klasse. Repräsentiert einen rechteckigen Bereich eines Bildes, definiert durch ein‑präzise Gleitkomma‑X‑ und Y‑Koordinaten seiner oberen linken Ecke sowie seiner Breite und Höhe. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die System::SmartPtr‑Klasse, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 2000
url: /de/cpp/system.drawing/rectanglef/
---
## RectangleF class


Repräsentiert einen rechteckigen Bereich eines Bildes, definiert durch ein‑präzise Gleitkomma‑X‑ und Y‑Koordinaten seiner oberen linken Ecke sowie seiner Breite und Höhe. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/)‑Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class RectangleF
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Contains](./contains/)(float, float) | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| [Contains](./contains/)(const PointF\&) | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| [Contains](./contains/)(const RectangleF\&) | Bestimmt, ob das angegebene Rechteck innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| [Equals](./equals/)(const RectangleF\&) const | Bestimmt, ob die vom aktuellen und vom angegebenen Objekt dargestellten Rechtecke identisch sind. |
| static [FromLTRB](./fromltrb/)(float, float, float, float) | Erstellt ein neues [RectangleF](./)-Objekt, das ein Rechteck mit den angegebenen Kantenpositionen darstellt. |
| [get_Bottom](./get_bottom/)() const | Gibt die y‑Koordinate der unteren Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_Height](./get_height/)() const | Gibt die Höhe des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob die X‑ und Y‑Koordinaten der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks sowie dessen Breite und Höhe den Wert 0 haben. |
| [get_Left](./get_left/)() const | Gibt die X‑Koordinate der linken Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_Location](./get_location/)() const | Gibt eine Instanz der Klasse [PointF](../pointf/) zurück, die den Ort der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| [get_Right](./get_right/)() const | Gibt die X‑Koordinate der rechten Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_Size](./get_size/)() const | Gibt eine Instanz der Klasse [SizeF](../sizef/) zurück, die die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| [get_Top](./get_top/)() const | Gibt die Y‑Koordinate der oberen Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_Width](./get_width/)() const | Gibt die Breite des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_X](./get_x/)() const | Gibt die X‑Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [get_Y](./get_y/)() const | Gibt die Y‑Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [GetHashCode](./gethashcode/)() const | Gibt einen Hash‑Code des aktuellen Objekts zurück. |
| [Inflate](./inflate/)(float, float) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks und behält dabei die Lage des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| [Inflate](./inflate/)(const SizeF\&) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks und behält dabei die Lage des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die durch die Breiten‑ und Höhenwerte des angegebenen Größenobjekts festgelegten Beträge entsprechend vergrößert. |
| static [Inflate](./inflate/)(const RectangleF\&, float, float) | Erhöht die Breite und Höhe des vom angegebenen Objekt dargestellten Rechtecks und behält dabei die Lage des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| [Intersect](./intersect/)(const RectangleF\&) | Ersetzt das vom aktuellen Objekt dargestellte Rechteck durch das Rechteck, das sich aus seiner Schnittmenge mit dem vom angegebenen Objekt dargestellten Rechteck ergibt. |
| static [Intersect](./intersect/)(const RectangleF\&, const RectangleF\&) | Gibt ein Rechteck zurück, das das Ergebnis der Schnittmenge der angegebenen Rechtecke ist. |
| [IntersectsWith](./intersectswith/)(const RectangleF\&) | Bestimmt, ob die vom aktuellen und vom angegebenen Objekt dargestellten Rechtecke sich überschneiden. |
| [Offset](./offset/)(const PointF\&) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Beträge. |
| [Offset](./offset/)(float, float) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Beträge. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Gibt immer true zurück. |
| [operator==](./operator==/)(std::nullptr_t) const | Gibt immer false zurück. |
| [RectangleF](./rectanglef/)() | Konstruiert eine neue Instanz des [RectangleF](./)-Objekts, das ein Rechteck mit X- und Y-Koordinaten sowie Breiten- und Höhenwerten von 0 darstellt. |
| [RectangleF](./rectanglef/)(float, float, float, float) | Konstruiert eine neue Instanz des [RectangleF](./)-Objekts, das ein Rechteck mit den angegebenen Koordinaten seiner oberen linken Ecke sowie Breite und Höhe darstellt. |
| [RectangleF](./rectanglef/)(const PointF\&, const SizeF\&) | Konstruiert eine neue Instanz des [RectangleF](./)-Objekts, das ein Rechteck mit den Koordinaten seiner oberen linken Ecke, angegeben als Instanz der [PointF](../pointf/)-Klasse, und seiner Breite und Höhe als Instanz der [SizeF](../sizef/)-Klasse, darstellt. |
| explicit [RectangleF](./rectanglef/)(const Rectangle\&) | Konstruiert eine neue Instanz des [RectangleF](./)-Objekts, das das dem angegebenen Rechteck entsprechende Rechteck darstellt. |
| [set_Height](./set_height/)(float) | Setzt die Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| [set_Location](./set_location/)(PointF) | Setzt die Position der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| [set_Size](./set_size/)(SizeF) | Setzt die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| [set_Width](./set_width/)(float) | Setzt die Breite des vom aktuellen Objekt dargestellten Rechtecks. |
| [set_X](./set_x/)(float) | Setzt die X‑Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| [set_Y](./set_y/)(float) | Setzt die Y‑Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des aktuellen Objekts zurück. |
| static [Union](./union/)(const RectangleF\&, const RectangleF\&) | Gibt ein Rechteck zurück, das das Ergebnis der Vereinigung der angegebenen Rechtecke ist. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Ein leeres Rechteck, d. h. ein Rechteck, dessen Positions‑ und Größenwerte Null sind. |
## Siehe auch

* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
