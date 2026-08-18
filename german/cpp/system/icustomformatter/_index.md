---
title: "System::ICustomFormatter Klasse"
linktitle: "ICustomFormatter"
second_title: "Aspose.PUB für C++"
description: "System::ICustomFormatter Klasse. Definiert eine Methode, die eine benutzerdefinierte Formatierung einer Zeichenkettenrepräsentation eines Wertes, der durch das angegebene Objekt dargestellt wird, durchführt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr‑Pointer ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 3500
url: /de/cpp/system/icustomformatter/
---
## ICustomFormatter class


Definiert eine Methode, die eine benutzerdefinierte Formatierung einer Zeichenkettenrepräsentation eines Wertes, der durch das angegebene Objekt dargestellt wird, durchführt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [Format](./format/)(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) | Gibt eine Zeichenkettenrepräsentation eines Wertes zurück, der vom aktuellen Objekt mit dem angegebenen Format dargestellt wird. |
## Siehe auch

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
