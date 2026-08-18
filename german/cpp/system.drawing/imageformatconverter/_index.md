---
title: "System::Drawing::ImageFormatConverter Klasse"
linktitle: "ImageFormatConverter"
second_title: "Aspose.PUB für C++"
description: "System::Drawing::ImageFormatConverter Klasse. Konvertiert ImageFormat-Objekte von einem Datentyp in einen anderen. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1400
url: /de/cpp/system.drawing/imageformatconverter/
---
## ImageFormatConverter class


Konvertiert ImageFormat-Objekte von einem Datentyp in einen anderen. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ImageFormatConverter : public System::ComponentModel::TypeConverter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&) override | Konvertiert Objekte. |
| [ConvertTo](./convertto/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) override | Konvertiert ein Objekt in einen bestimmten Typ. |
| [ImageFormatConverter](./imageformatconverter/)() | Erstellt eine neue Instanz von [ImageFormatConverter](./). |
## Siehe auch

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PUB for C++](../../)
