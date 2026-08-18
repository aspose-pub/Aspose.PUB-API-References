---
title: "System::Globalization::SortVersion Klasse"
linktitle: "SortVersion"
second_title: "Aspose.PUB für C++"
description: "System::Globalization::SortVersion Klasse. Liefert Informationen über die Unicode-Version, die zum Vergleichen und Sortieren von Zeichenfolgen verwendet wird. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 2300
url: /de/cpp/system.globalization/sortversion/
---
## SortVersion class


Stellt Informationen über die Unicode-Version bereit, die zum Vergleichen und Sortieren von Zeichenfolgen verwendet wird. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class SortVersion : public System::IEquatable<SharedPtr<SortVersion>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<SortVersion\>) override | Überprüft, ob die aktuelle [SortVersion](./)-Instanz gleich einem angegebenen [SortVersion](./)-Objekt ist. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Überprüft, ob die aktuelle [SortVersion](./)-Instanz gleich einem angegebenen [SortVersion](./)-Objekt ist. |
| [get_FullVersion](./get_fullversion/)() | Liefert die vollständige Versionsnummer. |
| [get_SortId](./get_sortid/)() | Liefert den eindeutigen Bezeichner für dieses Objekt. |
| [GetHashCode](./gethashcode/)() const override | Liefert den Hash‑Code für das aktuelle Objekt. |
| [operator!=](./operator!=/)(const SortVersion\&) | Überprüft, ob die aktuelle [SortVersion](./)-Instanz ungleich einem angegebenen [SortVersion](./)-Objekt ist. |
| [operator=](./operator=/)(const SortVersion\&) |  |
| [operator==](./operator==/)(const SortVersion\&) | Überprüft, ob die aktuelle [SortVersion](./)-Instanz gleich einem angegebenen [SortVersion](./)-Objekt ist. |
| [SortVersion](./sortversion/)(int, const Guid\&) | RTTI-Informationen. |
| [SortVersion](./sortversion/)(const SortVersion\&) |  |
## Siehe auch

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
