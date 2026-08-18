---
title: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef"
linktitle: "AnyOfDecimal"
second_title: "Aspose.PUB für C++"
description: "System::TestPredicates::TypeTraits::AnyOfDecimal typedef. Prüft, ob mindestens ein Typargument System::Decimal ist. Falls ja, wird das Member value auf true gesetzt, andernfalls ist es false in C++."
type: docs
weight: 100
url: /de/cpp/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


Prüft, ob mindestens ein Typargument [System::Decimal](../../system/decimal/) ist. Falls ja, wird das Member value auf true gesetzt, andernfalls ist es false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal =  std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## Siehe auch

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.PUB for C++](../../)
