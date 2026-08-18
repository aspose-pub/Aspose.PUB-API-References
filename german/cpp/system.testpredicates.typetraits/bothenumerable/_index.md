---
title: "System::TestPredicates::TypeTraits::BothEnumerable typedef"
linktitle: "BothEnumerable"
second_title: "Aspose.PUB für C++"
description: "System::TestPredicates::TypeTraits::BothEnumerable typedef. Prüft, ob beide Typargumente IEnumerable sind. Wenn ja, wird das Wertmitglied auf true gesetzt, andernfalls auf false in C++."
type: docs
weight: 400
url: /de/cpp/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable typedef


Überprüft, ob beide Typargumente IEnumerable sind. Wenn ja, wird das Member value auf true gesetzt, andernfalls auf false.

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable =  std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```


## Siehe auch

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PUB for C++](../../)
