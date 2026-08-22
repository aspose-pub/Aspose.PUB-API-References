---
title: "System::Func sınıfı"
linktitle: "Func"
second_title: "Aspose.PUB için C++"
description: "System::Func sınıfı. Fonksiyon temsilcisi. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. C++'ta bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 2800
url: /tr/cpp/system/func/
---
## Func class


Fonksiyon temsilcisi. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer ya da referans olarak geçirilmelidir. Bu tipin nesnelerini yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


| Parametre | Açıklama |
| --- | --- |
| Args | Çağrı argümanları, ardından zorunlu dönüş tipi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Func](./func/)() | null-Func oluşturan varsayılan yapıcı. |
| [Func](./func/)(T\&&) | [Func](./) nesnesini oluşturan ve ona değer (gerçek geri çağırma ya da nullptr) atayan yapıcı. |
| [Func](./func/)(const Func\&) | Kopya yapıcı. |
| [Func](./func/)(Func\&&) | Taşıma yapıcı. |
| [operator=](./operator=/)(const Func\&) | Kopya atama. |
| [operator=](./operator=/)(Func\&&) | Taşıma atama. |
| [~Func](./~func/)() | Yıkıcı. |
## Açıklamalar



```cpp
#include "system/func.h"
#include <iostream>

// Bu fonksiyon, System::Func temsilcisinin bir örneğini parametre olarak kabul eder.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // System::Func temsilcisinin bir örneğini oluştur.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Oluşturulan örneği fonksiyon argümanı olarak geç.
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

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
