---
title: "System::Reflection::MethodBase sınıfı"
linktitle: "MethodBase"
second_title: "Aspose.PUB için C++"
description: "System::Reflection::MethodBase sınıfı. Yöntem hakkında temel bilgi. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve C++'ta fonksiyonlara argüman olarak geçirmek için bu işaretçiyi kullanın."
type: docs
weight: 800
url: /tr/cpp/system.reflection/methodbase/
---
## MethodBase class


Yöntem hakkında temel bilgi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Üyenin türünü gösterme - yöntem, yapıcı, olay vb. |
| static [GetCurrentMethod](./getcurrentmethod/)(const String\&) | Bu yöntem, geçerli yöntem adını almayı sağlar. Çevirmen, ASPOSE_CURRENT_FUNCTION parametresini otomatik olarak yerleştirir. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(MethodBase, CODEPORTING_ARGS(const String\&full_name), CODEPORTING_ARGS(full_name)) |  |
| [MethodBase](./methodbase/)() | [MethodBase](./) sınıfının yeni bir örneğini başlatır. |
## Ayrıca Bakınız

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
