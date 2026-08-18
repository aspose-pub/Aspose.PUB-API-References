---
title: "System::Runtime::Serialization Namespace"
linktitle: "System::Runtime::Serialization"
second_title: "Aspose.PUB für C++"
description: "Wie man das System::Runtime::Serialization Namespace in C++ verwendet."
type: docs
weight: 3700
url: /de/cpp/system.runtime.serialization/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [FormatterConverter](./formatterconverter/) | Stellt eine Basisimplementierung des [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) Interfaces dar. |
| [IFormatterConverter](./iformatterconverter/) | Bietet die Verbindung zwischen einer Instanz von [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) und der vom Formatter bereitgestellten Klasse, die am besten geeignet ist, die Daten innerhalb des [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) zu analysieren. |
| [ISerializable](./iserializable/) | Schnittstelle eines Objekts, das serialisiert werden kann. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SerializationInfo](./serializationinfo/) | Enthält eine Menge benannter Felder, die ein serialisiertes Objekt repräsentieren. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [StreamingContext](./streamingcontext/) | Dummy-Klasse, um die Kompilierung von übersetzten Klassen, die StreamingContext verwenden, zu ermöglichen. Verwalten Sie Instanzen dieser Klasse nicht mit [SmartPtr](../system/smartptr/); sie müssen ausschließlich auf dem Stack alloziert werden. |
