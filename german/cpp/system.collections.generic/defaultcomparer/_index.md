---
title: "System::Collections::Generic::DefaultComparer class"
linktitle: "DefaultComparer"
second_title: "Aspose.PUB für C++"
description: "System::Collections::Generic::DefaultComparer class. Standardvergleichsklasse. Verwendet die Operatoren < und == zum Vergleich von Werten. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr‑Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen in C++ zu übergeben."
type: docs
weight: 1000
url: /de/cpp/system.collections.generic/defaultcomparer/
---
## DefaultComparer class


Standardvergleichsklasse. Verwendet die Operatoren < und == zum Vergleich von Werten. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)‑Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<class T>class DefaultComparer : public System::Collections::Generic::IComparer<T>
```


| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der verglichen wird. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Compare](./compare/)(typename ThisType::args_type, typename ThisType::args_type) const override | RTTI-Informationen. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [BaseType](./basetype/) | Implementiertes Interface. |
| [ThisType](./thistype/) | Aktueller Typ. |

## Siehe auch

* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PUB for C++](../../)
