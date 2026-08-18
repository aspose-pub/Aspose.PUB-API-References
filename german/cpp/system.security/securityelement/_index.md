---
title: "System::Security::SecurityElement class"
linktitle: "SecurityElement"
second_title: "Aspose.PUB für C++"
description: "System::Security::SecurityElement class. XML-Objektmodell zum Kodieren von Sicherheitsobjekten. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 300
url: /de/cpp/system.security/securityelement/
---
## SecurityElement class


XML-Objektmodell zum Kodieren von Sicherheitsobjekten. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SecurityElement : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Fügt dem Tag ein Attribut hinzu. |
| [AddChild](./addchild/)(SecurityElement) | Fügt ein untergeordnetes Tag hinzu. |
| [Attribute](./attribute/)(const String\&) | Liest den Attributwert. |
| [Copy](./copy/)() | Klonet das Tag. |
| [Equal](./equal/)(SecurityElement) | Prüft die Gleichheit von Parametern. |
| static [Escape](./escape/)(const String\&) | Escaped Zeichen in einer XML-Zeichenkette. |
| static [FromString](./fromstring/)(const String\&) | Erstellt ein Element aus XML-Code. |
| [get_Attributes](./get_attributes/)() | Liest die Tag-Attribute. |
| [get_Children](./get_children/)() | Liest die untergeordneten Objekte des Tags. |
| [get_Tag](./get_tag/)() | Liest den Tag-Namen. |
| [get_Text](./get_text/)() | Liest den inneren Text des Tags. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Prüft, ob der Attributname gültig ist. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Prüft, ob der Attributwert gültig ist. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Prüft, ob das Tag gültig ist. |
| static [IsValidText](./isvalidtext/)(const String\&) | Prüft, ob der Text gültig ist. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | Liest das untergeordnete Tag nach Namen. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Liest den inneren Text des untergeordneten Tags anhand des Tag-Namens. |
| [SecurityElement](./securityelement/)(const String\&) | Konstruktor. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Konstruktor. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Setzt Tag-Attribute. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Setzt untergeordnete Objekte des Tags. |
| [set_Tag](./set_tag/)(const String\&) | Setzt den Tag-Namen. |
| [set_Text](./set_text/)(const String\&) | Setzt den inneren Text des Tags. |
| [ToString](./tostring/)() const override | Konvertiert Tag in einen String. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PUB for C++](../../)
