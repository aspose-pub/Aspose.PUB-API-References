---
title: "System::Net::Http::Headers::ContentDispositionHeaderValue Klasse"
linktitle: "ContentDispositionHeaderValue"
second_title: "Aspose.PUB für C++"
description: "System::Net::Http::Headers::ContentDispositionHeaderValue Klasse. Stellt einen Wert des ''Content-Disposition''-Headers dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben in C++."
type: docs
weight: 300
url: /de/cpp/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue class


Stellt einen Wert des 'Content-Disposition'-Headers dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Konstruiert eine neue Instanz. |
| [ContentDispositionHeaderValue](./contentdispositionheadervalue/)(String) | Konstruiert eine neue Instanz. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Vergleicht Objekte anhand der C#-Semantik von [Object.Equals](../../system/object/equals/). |
| [get_CreationDate](./get_creationdate/)() | Liefert das Erstellungsdatum der Datei. |
| [get_DispositionType](./get_dispositiontype/)() | RTTI-Informationen. |
| [get_FileName](./get_filename/)() | Liefert einen Wert, der bestimmt, wie ein Dateiname für die Speicherung der Nachrichten-Payload konstruiert wird. Er wird verwendet, wenn die Entität getrennt und in einer separaten Datei gespeichert wird. |
| [get_FileNameStar](./get_filenamestar/)() | Liefert einen Wert, der bestimmt, wie Dateinamen für die Speicherung der Nachrichten-Payload konstruiert werden. Er wird verwendet, wenn die Entitäten getrennt und in separaten Dateien gespeichert werden. |
| [get_ModificationDate](./get_modificationdate/)() | Liefert das Änderungsdatum der Datei. |
| [get_Name](./get_name/)() | Liefert einen Namen für einen Teil des Inhaltskörpers. |
| [get_Parameters](./get_parameters/)() | Gibt eine Parametersammlung des 'Content-Disposition'-Headers zurück. |
| [get_ReadDate](./get_readdate/)() | Liefert das Datum, an dem die Datei zuletzt gelesen wurde. |
| [get_Size](./get_size/)() | Liefert eine ungefähre Dateigröße. |
| static [GetDispositionTypeLength](./getdispositiontypelength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der Klasse [ContentDispositionHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| static [Parse](./parse/)(String) | Konvertiert einen übergebenen String in eine Instanz der Klasse [ContentDispositionHeaderValue](./). |
| [set_CreationDate](./set_creationdate/)(Nullable\<DateTimeOffset\>) | Setzt das Erstellungsdatum der Datei. |
| [set_DispositionType](./set_dispositiontype/)(String) | Setzt einen Disposition-Typ. |
| [set_FileName](./set_filename/)(String) | Setzt einen Wert, der bestimmt, wie ein Dateiname für die Speicherung der Nachrichten-Payload konstruiert wird. Er wird verwendet, wenn die Entität getrennt und in einer separaten Datei gespeichert wird. |
| [set_FileNameStar](./set_filenamestar/)(String) | Setzt einen Wert, der bestimmt, wie Dateinamen für die Speicherung der Nachrichten-Payload konstruiert werden. Er wird verwendet, wenn die Entitäten getrennt und in separaten Dateien gespeichert werden. |
| [set_ModificationDate](./set_modificationdate/)(Nullable\<DateTimeOffset\>) | Setzt das Änderungsdatum der Datei. |
| [set_Name](./set_name/)(String) | Setzt einen Namen für einen Teil des Inhaltskörpers. |
| [set_ReadDate](./set_readdate/)(Nullable\<DateTimeOffset\>) | Setzt das Datum, an dem die Datei zuletzt gelesen wurde. |
| [set_Size](./set_size/)(Nullable\<int64_t\>) | Setzt eine ungefähre Dateigröße. |
| [ToString](./tostring/)() const override | Analog zur C#‑Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) | Versucht, einen übergebenen String in eine Instanz der Klasse [ContentDispositionHeaderValue](./) zu konvertieren. |
## Siehe auch

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PUB for C++](../../)
