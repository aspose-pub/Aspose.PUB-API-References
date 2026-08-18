---
title: "System::Resources::ResourceManager Klasse"
linktitle: "ResourceManager"
second_title: "Aspose.PUB für C++"
description: "System::Resources::ResourceManager Klasse. Stellt eine API zur Verwaltung von Ressourcen bereit. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 100
url: /de/cpp/system.resources/resourcemanager/
---
## ResourceManager class


Bietet eine API zur Verwaltung von Ressourcen. Nicht implementiert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ResourceManager : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [GetObject__](./getobject__/)(String) | Liest ein Objekt aus der Ressource. Der Name ist nicht GetObject(), um das Problem mit der Definition von GetObjectA zu umgehen. |
| virtual [GetObject__](./getobject__/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Liest ein Objekt aus der Ressource. Der Name ist nicht GetObject(), um das Problem mit der Definition von GetObjectA zu umgehen. |
| virtual [GetString](./getstring/)(String) | Liest eine Zeichenkettenressource. |
| virtual [GetString](./getstring/)(String, SharedPtr\<System::Globalization::CultureInfo\>) | Liest eine Zeichenkettenressource. |
| [ResourceManager](./resourcemanager/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | RTTI-Informationen. |
## Siehe auch

* Class [Object](../../system/object/)
* Namespace [System::Resources](../)
* Library [Aspose.PUB for C++](../../)
