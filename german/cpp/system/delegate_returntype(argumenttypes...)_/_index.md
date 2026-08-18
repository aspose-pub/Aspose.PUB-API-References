---
title: "System::Delegate< ReturnType(ArgumentTypes...)>-Klasse"
linktitle: "Delegate< ReturnType(ArgumentTypes...)>"
second_title: "Aspose.PUB für C++"
description: "System::Delegate< ReturnType(ArgumentTypes...)>-Klasse. Stellt einen Zeiger auf eine Funktion, Methode oder ein Funktionsobjekt dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr-Klasse, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 2100
url: /de/cpp/system/delegate_returntype(argumenttypes...)_/
---
## Delegate< ReturnType(ArgumentTypes...)> class


Stellt einen Zeiger auf eine Funktion, Methode oder ein Funktionsobjekt dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/)-Klasse, um Objekte dieses Typs zu verwalten.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parameter | Beschreibung |
| --- | --- |
| ReturnType | Der Rückgabetyp einer Funktion, Methode oder eines Funktionsobjektzeigers, der durch die Klasse dargestellt wird |
| ArgumentTypes | Die Argumentliste einer Funktion, Methode oder eines Funktionsobjektzeigers, der durch die Klasse dargestellt wird |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Delegate](./delegate/)() | Standardkonstruktor. Erstellt das Delegate-Objekt, das auf nichts zeigt. |
| [Delegate](./delegate/)(const Delegate\&) |  |
| [Delegate](./delegate/)(Delegate\&&) | Move-Kopierkonstruktor. Übernimmt den Besitz einer Entität, auf die das angegebene Delegate zeigt. |
| [Delegate](./delegate/)(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Konstruktor. Erstellt ein Delegate-Objekt aus dem angegebenen Zeiger auf eine freie Funktion oder statische Methode. |
| [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Konstruktor. Erstellt ein Delegate aus dem angegebenen Zeiger auf das Funktionsobjekt, das von std::bind() erzeugt wurde. |
| [Delegate](./delegate/)(int, T\&) | Konstruktor. Erstellt ein Delegate aus dem angegebenen Funktionsobjekt. |
| [Delegate](./delegate/)(long, T\&&) | Move-Konstruktor. Erstellt ein Delegate aus dem angegebenen Funktionsobjekt. |
| [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Konstruktor. Erstellt ein Delegate, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt. |
| [Delegate](./delegate/)(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) | Konstruktor. Erstellt ein Delegate, das auf die angegebene nicht-statische Methode des angegebenen Objekts zeigt. |
| [Delegate](./delegate/)(std::function\<R(Args...)>) | Erstellt ein Delegate-Objekt, das auf ein std::function-Funktionsobjekt zeigt. |
| [Empty](./empty/)() const | Bestimmt, ob das aktuelle Delegate-Objekt leer ist, d. h. auf keine Entität zeigt. |
| [operator()](./operator()/)(ArgumentTypes...) const | Ruft eine Funktion, Methode oder ein Funktionsobjekt auf, auf das das aktuelle Delegate-Objekt zeigt. |
| [operator=](./operator=/)(const Delegate\&) |  |
| [operator=](./operator=/)(Delegate\&&) | Move-Zuweisungsoperator. Übernimmt den Besitz einer Entität, auf die das angegebene Delegate zeigt. |
| [operator==](./operator==/)(const Delegate\&) const | Vergleicht zwei Delegate-Objekte, um zu prüfen, ob sie auf dieselbe Entität zeigen. |
## Hinweise



```cpp
#include "system/delegate.h"
#include <iostream>

// Deklariere das Delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Weise der Variablen die Adresse der PrintMessage-Funktion zu.
  Message mes = Message(&PrintMessage);

  // Rufe die Funktion auf.
  mes();

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
