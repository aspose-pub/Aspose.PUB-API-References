---
title: "System::Globalization::SortVersion sınıfı"
linktitle: "SortVersion"
second_title: "Aspose.PUB için C++"
description: "System::Globalization::SortVersion sınıfı. Dizeleri karşılaştırmak ve sıralamak için kullanılan Unicode sürümü hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 2300
url: /tr/cpp/system.globalization/sortversion/
---
## SortVersion class


Dizeleri karşılaştırmak ve sıralamak için kullanılan Unicode sürümü hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına (stack) ya da operator new ile oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class SortVersion : public System::IEquatable<SharedPtr<SortVersion>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<SortVersion\>) override | Mevcut [SortVersion](./) örneğinin belirtilen [SortVersion](./) nesnesine eşit olup olmadığını denetler. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Mevcut [SortVersion](./) örneğinin belirtilen [SortVersion](./) nesnesine eşit olup olmadığını denetler. |
| [get_FullVersion](./get_fullversion/)() | Tam sürüm numarasını alır. |
| [get_SortId](./get_sortid/)() | Bu nesne için benzersiz tanımlayıcıyı alır. |
| [GetHashCode](./gethashcode/)() const override | Mevcut nesne için karma kodunu alır. |
| [operator!=](./operator!=/)(const SortVersion\&) | Mevcut [SortVersion](./) örneğinin belirtilen [SortVersion](./) nesnesine eşit olmadığını denetler. |
| [operator=](./operator=/)(const SortVersion\&) |  |
| [operator==](./operator==/)(const SortVersion\&) | Mevcut [SortVersion](./) örneğinin belirtilen [SortVersion](./) nesnesine eşit olup olmadığını denetler. |
| [SortVersion](./sortversion/)(int, const Guid\&) | RTTI bilgisi. |
| [SortVersion](./sortversion/)(const SortVersion\&) |  |
## Ayrıca Bakınız

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PUB for C++](../../)
