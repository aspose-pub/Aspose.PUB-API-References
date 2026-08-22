---
title: "System::Text::RegularExpressions::Group class"
linktitle: "Group"
second_title: "Aspose.PUB için C++"
description: "System::Text::RegularExpressions::Group sınıfı. Tek yakalama grubu tarafından yapılan eşleştirmenin sonucu. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 300
url: /tr/cpp/system.text.regularexpressions/group/
---
## Group class


Tek yakalama grubu tarafından yapılan eşleştirmenin sonucu. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına ya da operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Gruba yakalama ekler. |
| [get_Captures](./get_captures/)() | Mevcut yakalamaları alır. |
| [get_Success](./get_success/)() | Bu grup için yakalamanın başarılı olup olmadığını kontrol eder. |
| [Group](./group/)(const UStringPtr\&, int, int) | Yapıcı. |
| [Group](./group/)() | Boş grup için kurucu. |
## Ayrıca Bakınız

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PUB for C++](../../)
