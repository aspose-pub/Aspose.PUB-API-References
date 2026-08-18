---
title: "System::Xml::XmlWriterSettings class"
linktitle: "XmlWriterSettings"
second_title: "Aspose.PUB für C++"
description: "System::Xml::XmlWriterSettings-Klasse. Gibt einen Satz von Funktionen an, die beim XmlWriter-Objekt unterstützt werden, das mit der XmlWriter::Create‑Methode in C++ erstellt wird."
type: docs
weight: 4500
url: /de/cpp/system.xml/xmlwritersettings/
---
## XmlWriterSettings class


Gibt einen Satz von Funktionen an, die beim [XmlWriter](../xmlwriter/)-Objekt unterstützt werden, das mit der [XmlWriter::Create](../xmlwriter/create/)-Methode erstellt wird.

```cpp
class XmlWriterSettings : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone](./clone/)() | Erstellt eine Kopie der [XmlWriterSettings](./)-Instanz. |
| [get_CheckCharacters](./get_checkcharacters/)() | Gibt einen Wert zurück, der angibt, ob der XML‑Writer prüfen soll, dass alle Zeichen im Dokument dem Abschnitt „2.2 Characters“ der W3C‑[XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) entsprechen. |
| [get_CloseOutput](./get_closeoutput/)() | Gibt einen Wert zurück, der angibt, ob der [XmlWriter](../xmlwriter/) beim Aufruf der [XmlWriter::Close](../xmlwriter/close/)-Methode auch den zugrunde liegenden Stream oder TextWriter schließen soll. |
| [get_ConformanceLevel](./get_conformancelevel/)() | Gibt das Konformitätsniveau zurück, das der XML‑Writer bei der XML‑Ausgabe überprüft. |
| [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Gibt einen Wert zurück, der angibt, ob der [XmlWriter](../xmlwriter/) URI‑Attribute nicht escaped. |
| [get_Encoding](./get_encoding/)() | Gibt den zu verwendenden Textkodierungstyp zurück. |
| [get_Indent](./get_indent/)() | Gibt einen Wert zurück, der angibt, ob Elemente eingerückt werden sollen. |
| [get_IndentChars](./get_indentchars/)() | Gibt die Zeichenkette zurück, die beim Einrücken verwendet wird. Diese Einstellung wird verwendet, wenn der Wert [XmlWriterSettings::set_Indent](./set_indent/) auf **true** gesetzt ist. |
| [get_NamespaceHandling](./get_namespacehandling/)() | Gibt einen Wert zurück, der angibt, ob der [XmlWriter](../xmlwriter/) doppelte Namespace-Deklarationen beim Schreiben von XML-Inhalt entfernen soll. Das Standardverhalten ist, dass der Writer alle Namespace-Deklarationen ausgibt, die im Namespace-Resolver des Writers vorhanden sind. |
| [get_NewLineChars](./get_newlinechars/)() | Gibt die Zeichenkette zurück, die für Zeilenumbrüche verwendet wird. |
| [get_NewLineHandling](./get_newlinehandling/)() | Gibt einen Wert zurück, der angibt, ob Zeilenumbrüche in der Ausgabe normalisiert werden sollen. |
| [get_NewLineOnAttributes](./get_newlineonattributes/)() | Gibt einen Wert zurück, der angibt, ob Attribute in einer neuen Zeile geschrieben werden sollen. |
| [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Gibt einen Wert zurück, der angibt, ob eine XML-Deklaration weggelassen werden soll. |
| [get_OutputMethod](./get_outputmethod/)() | Gibt die Methode zurück, die zum Serialisieren der [XmlWriter](../xmlwriter/)-Ausgabe verwendet wird. |
| [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Gibt einen Wert zurück, der angibt, ob der [XmlWriter](../xmlwriter/) beim Aufruf der Methode [XmlWriter::Close](../xmlwriter/close/) Schließ-Tags zu allen nicht geschlossenen Element-Tags hinzufügt. |
| [Reset](./reset/)() | Setzt die Mitglieder der Einstellungsklasse auf ihre Standardwerte zurück. |
| [set_CheckCharacters](./set_checkcharacters/)(bool) | Setzt einen Wert, der angibt, ob der XML-Writer prüfen soll, dass alle Zeichen im Dokument dem Abschnitt \"2.2 Characters\" der W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) entsprechen. |
| [set_CloseOutput](./set_closeoutput/)(bool) | Setzt einen Wert, der angibt, ob der [XmlWriter](../xmlwriter/) beim Aufruf der Methode [XmlWriter::Close](../xmlwriter/close/) auch den zugrunde liegenden Stream oder TextWriter schließen soll. |
| [set_ConformanceLevel](./set_conformancelevel/)(System::Xml::ConformanceLevel) | Setzt das Konformitätsniveau, das der XML-Writer bei der Überprüfung der XML-Ausgabe berücksichtigt. |
| [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(bool) | Setzt einen Wert, der angibt, ob der [XmlWriter](../xmlwriter/) URI-Attribute nicht escaped. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Setzt den zu verwendenden Typ der Textkodierung. |
| [set_Indent](./set_indent/)(bool) | Setzt einen Wert, der angibt, ob Elemente eingerückt werden sollen. |
| [set_IndentChars](./set_indentchars/)(const String\&) | Setzt die Zeichenkette, die beim Einrücken verwendet wird. Diese Einstellung wird verwendet, wenn der Wert [XmlWriterSettings::set_Indent](./set_indent/) auf **true** gesetzt ist. |
| [set_NamespaceHandling](./set_namespacehandling/)(System::Xml::NamespaceHandling) | Setzt einen Wert, der angibt, ob der [XmlWriter](../xmlwriter/) doppelte Namespace-Deklarationen beim Schreiben von XML-Inhalt entfernen soll. Das Standardverhalten ist, dass der Writer alle Namespace-Deklarationen ausgibt, die im Namespace-Resolver des Writers vorhanden sind. |
| [set_NewLineChars](./set_newlinechars/)(const String\&) | Setzt die Zeichenkette, die für Zeilenumbrüche verwendet wird. |
| [set_NewLineHandling](./set_newlinehandling/)(System::Xml::NewLineHandling) | Setzt einen Wert, der angibt, ob Zeilenumbrüche in der Ausgabe normalisiert werden sollen. |
| [set_NewLineOnAttributes](./set_newlineonattributes/)(bool) | Setzt einen Wert, der angibt, ob Attribute in einer neuen Zeile geschrieben werden sollen. |
| [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(bool) | Setzt einen Wert, der angibt, ob eine XML-Deklaration weggelassen werden soll. |
| [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(bool) | Setzt einen Wert, der angibt, ob der [XmlWriter](../xmlwriter/) beim Aufruf der Methode [XmlWriter::Close](../xmlwriter/close/) Schließ-Tags zu allen nicht geschlossenen Element-Tags hinzufügt. |
| [XmlWriterSettings](./xmlwritersettings/)() | Initialisiert eine neue Instanz der Klasse [XmlWriterSettings](./). |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared Pointer auf eine Instanz dieser Klasse. |
## Hinweise



Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
