---
title: "System::Action typedef"
linktitle: "Action"
second_title: "Aspose.PUB için C++"
description: "System::Action typedef. C++'da dönüş değeri olmayan yöntemlere referans veren bir delege türüdür."
type: docs
weight: 9100
url: /tr/cpp/system/action/
---
## Action typedef


Dönüş değeri olmayan yöntemleri referans alan delege tipi.

```cpp
using System::Action =  MulticastDelegate<void(Args...)>
```

## Açıklamalar



```cpp
#include <system/action.h>

using namespace System;

// Geçilen dizeyi yazdıran fonksiyon.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action'ın bir örneğini oluştur.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Action'ı çağır.
  action(u"Hello, world!");

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
