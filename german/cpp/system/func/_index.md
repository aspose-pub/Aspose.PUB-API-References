---
title: "System::Func Klasse"
linktitle: "Func"
second_title: "Aspose.PUB für C++"
description: "System::Func Klasse. Funktions-Delegat. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs in C++ zu verwalten."
type: docs
weight: 2800
url: /de/cpp/system/func/
---
## Func class


Funktions-Delegat. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


| Parameter | Beschreibung |
| --- | --- |
| Args | Aufrufargumente, dann obligatorischer Rückgabetyp. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Func](./func/)() | Standardkonstruktor, der ein null-Func erstellt. |
| [Func](./func/)(T\&&) | Konstruktor, der ein [Func](./)-Objekt erstellt und ihm einen Wert zuweist (entweder einen tatsächlichen Callback oder nullptr). |
| [Func](./func/)(const Func\&) | Kopierkonstruktor. |
| [Func](./func/)(Func\&&) | Move‑Konstruktor. |
| [operator=](./operator=/)(const Func\&) | Kopierzuweisung. |
| [operator=](./operator=/)(Func\&&) | Move-Zuweisung. |
| [~Func](./~func/)() | Destruktor. |
## Hinweise



```cpp
#include "system/func.h"
#include <iostream>

// Diese Funktion akzeptiert eine Instanz des System::Func Delegaten als Parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Erstellen Sie eine Instanz des System::Func Delegaten.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Übergeben Sie die erstellte Instanz als Funktionsargument.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
This code example produces the following output:
1
4
9
*/
```

## Siehe auch

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
