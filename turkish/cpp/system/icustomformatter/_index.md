---
title: "System::ICustomFormatter sınıfı"
linktitle: "ICustomFormatter"
second_title: "Aspose.PUB için C++"
description: "System::ICustomFormatter sınıfı. Belirtilen nesne tarafından temsil edilen bir değerin dize temsili için özel biçimlendirme yapan bir yöntemi tanımlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına ya da new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın C++'ta."
type: docs
weight: 3500
url: /tr/cpp/system/icustomformatter/
---
## ICustomFormatter class


Belirtilen nesne tarafından temsil edilen bir değerin dize temsili için özel biçimlendirme yapan bir yöntemi tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığına ya da new operatörüyle oluşturulmamalıdır, aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class ICustomFormatter : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [Format](./format/)(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) | Geçerli nesne tarafından temsil edilen bir değerin belirtilen biçimi kullanılarak dize temsili döndürür. |
## Ayrıca Bakınız

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
