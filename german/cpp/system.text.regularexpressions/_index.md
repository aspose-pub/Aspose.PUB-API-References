---
title: "Namespace System::Text::RegularExpressions"
linktitle: "System::Text::RegularExpressions"
second_title: "Aspose.PUB für C++"
description: "Wie man den Namespace System::Text::RegularExpressions in C++ verwendet."
type: docs
weight: 4800
url: /de/cpp/system.text.regularexpressions/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Capture](./capture/) | Ergebnis einer einzelnen Subausdruck‑Übereinstimmung. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [CaptureCollection](./capturecollection/) | Liste der Captures, die von einer einzelnen Erfassungsgruppe durchgeführt wurden. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion‑Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Group](./group/) | Ergebnis des Matchings, das von einer einzelnen Erfassungsgruppe durchgeführt wird. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [GroupCollection](./groupcollection/) | Liste der Erfassungsgruppen in einem einzelnen Match. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) Sammlungszeiger. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden. |
| [Match](./match/) | [Single](../system/single/) Match eines regulären Ausdrucks über einen String. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [MatchCollection](./matchcollection/) | Sammlung von Matches, die durch wiederholtes Anwenden eines regulären Ausdrucks auf einen String erzeugt werden. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Regex](./regex/) | Regulärer Ausdruck, der einer C#-ähnlichen Syntax folgt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) Optionen. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [CaptureCollectionPtr](./capturecollectionptr/) | Zeiger auf Erfassungssammlung. |
| [CapturePtr](./captureptr/) | Zeiger auf einzelnes Erfassungsobjekt. |
| [GroupPtr](./groupptr/) | Zeiger auf Gruppe. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) Sammlungszeiger. |
| [MatchEvaluator](./matchevaluator/) | Delegattyp zur Auswertung eines Matches. |
| [MatchPtr](./matchptr/) | [Match](./match/) Zeiger. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) Zeiger. |
| [UStringPtr](./ustringptr/) | Gemeinsame UnicodeString, um Kopieren zu vermeiden. |
