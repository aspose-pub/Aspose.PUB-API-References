---
title: "System::TestPredicates::TypeTraits::BothArrayOrList typedef"
linktitle: "BothArrayOrList"
second_title: "Aspose.PUB für C++"
description: "System::TestPredicates::TypeTraits::BothArrayOrList typedef. Prüft, ob beide Typargumente Arrays oder Listen sind. Wenn ja, wird das Wertmitglied auf true gesetzt, andernfalls auf false in C++."
type: docs
weight: 300
url: /de/cpp/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Überprüft, ob beide Typargumente Arrays oder Listen sind. Wenn ja, wird das Member value auf true gesetzt, andernfalls auf false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList =  std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Siehe auch

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PUB for C++](../../)
