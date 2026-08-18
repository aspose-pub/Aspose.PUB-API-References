---
title: "System::Net::Http::Headers::MediaTypeHeaderValue Klasse"
linktitle: "MediaTypeHeaderValue"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::Headers::MediaTypeHeaderValue Klasse. Stellt einen MIME-Typ in einem Wert des ''Content-Type''-Headers dar. Objekte dieser Klasse sollten nur über die System::MakeObject()-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1200
url: /de/cpp/system.net.http.headers/mediatypeheadervalue/
---
## MediaTypeHeaderValue class


Stellt einen MIME-Typ in einem Wert des 'Content-Type'-Headers dar. Objekte dieser Klasse sollten nur über die [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class MediaTypeHeaderValue : public virtual System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Vergleicht Objekte anhand der C#-Semantik von [Object.Equals](../../system/object/equals/). |
| [get_CharSet](./get_charset/)() | RTTI-Informationen. |
| [get_MediaType](./get_mediatype/)() | Liest einen Wert des Media-Type-Headers. |
| [get_Parameters](./get_parameters/)() | Gibt die Werteparameter des Media-Type-Headers zurück. |
| [GetHashCode](./gethashcode/)() const override | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| static [GetMediaTypeLength](./getmediatypelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [MediaTypeHeaderValue](./) Klasse. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)() | Konstruiert eine neue Instanz. |
| [MediaTypeHeaderValue](./mediatypeheadervalue/)(String) | Konstruiert eine neue Instanz. |
| static [Parse](./parse/)(String) | Konvertiert einen übergebenen String in eine Instanz der [MediaTypeHeaderValue](./) Klasse. |
| [set_CharSet](./set_charset/)(String) | Setzt einen Zeichensatz. |
| [set_MediaType](./set_mediatype/)(String) | Setzt einen Wert des Media-Type-Headers. |
| [ToString](./tostring/)() const override | Analog zur C#‑Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) | Versucht, einen übergebenen String in eine Instanz der [MediaTypeHeaderValue](./) Klasse zu konvertieren. |
## Siehe auch

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
