---
title: "System::Drawing::Drawing2D::CustomLineCap Klasse"
linktitle: "CustomLineCap"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::Drawing2D::CustomLineCap Klasse. Stellt einen benutzerdefinierten Linienabschluss dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 400
url: /de/cpp/system.drawing.drawing2d/customlinecap/
---
## CustomLineCap class


Stellt einen benutzerdefinierten Linienabschluss dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben.

```cpp
class CustomLineCap : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Clone](./clone/)() | Gibt eine Kopie des aktuellen Objekts zurück. |
| [CustomLineCap](./customlinecap/)(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) | Erstellt eine neue Instanz der [CustomLineCap](./) Klasse, die einen benutzerdefinierten Linienabschluss mit den angegebenen Eigenschaften darstellt. |
| [Dispose](./dispose/)() | Gibt alle vom aktuellen Objekt erworbenen Betriebssystemressourcen frei. |
| [get_BaseCap](./get_basecap/)() const | Gibt den Basislinienabschluss zurück, aus dem dieser benutzerdefinierte Abschluss erstellt wurde. |
| [get_BaseInset](./get_baseinset/)() const | Gibt den Abstand zwischen der Linie und dem Abschluss zurück. |
| [get_StrokeJoin](./get_strokejoin/)() const | Gibt den LineJoin‑Wert zurück, der bestimmt, wie die Linien dieses benutzerdefinierten Abschlusses verbunden werden. |
| [get_WidthScale](./get_widthscale/)() const | Gibt die Skalierung dieses benutzerdefinierten Abschlusses zurück. |
| [GetStrokeCaps](./getstrokecaps/)(LineCap\&, LineCap\&) | Liefert die Start- und Endlinienabschlüsse des durch das aktuelle Objekt dargestellten benutzerdefinierten Abschlusses. |
| [set_BaseCap](./set_basecap/)(LineCap) | Setzt den Basislinienabschlusswert für diesen benutzerdefinierten Abschluss. |
| [set_BaseInset](./set_baseinset/)(float) | Setzt den Abstand zwischen der Linie und dem Abschluss. |
| [set_StrokeJoin](./set_strokejoin/)(LineJoin) | Setzt den LineJoin‑Wert, der bestimmt, wie die Linien dieses benutzerdefinierten Abschlusses verbunden werden. |
| [set_WidthScale](./set_widthscale/)(float) | Setzt den Skalierungswert dieses benutzerdefinierten Abschlusses. |
| [SetStrokeCaps](./setstrokecaps/)(LineCap, LineCap) | Setzt die Start- und Endlinienabschlüsse des durch das aktuelle Objekt dargestellten benutzerdefinierten Abschlusses. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PUB for C++](../../)
