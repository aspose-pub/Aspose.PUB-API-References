---
title: "System::Collections::Specialized::StringDictionary sınıfı"
linktitle: "StringDictionary"
second_title: "Aspose.PUB için C++"
description: "System::Collections::Specialized::StringDictionary sınıfı. Dizeden dizeye sözlük. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 500
url: /tr/cpp/system.collections.specialized/stringdictionary/
---
## StringDictionary class


[String](../../system/string/) to string dictionary. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringDictionary : public System::Collections::Generic::Dictionary<String, String>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const override | Belirli anahtardaki değeri alır. |
## Ayrıca Bakınız

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PUB for C++](../../)
