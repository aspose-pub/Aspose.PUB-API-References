---
title: "System::Reflection::MemberInfo sınıf"
linktitle: "MemberInfo"
second_title: "Aspose.PUB için C++"
description: "System::Reflection::MemberInfo sınıf. Üyeler hakkında yansıma bilgisi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'da fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 700
url: /tr/cpp/system.reflection/memberinfo/
---
## MemberInfo class


Üyeler hakkında yansıma bilgisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) veya operator new ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class MemberInfo : public System::Object
```

## Nested classes

* Class [TypeInternal](./typeinternal/)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Koleksiyona öznitelik ekler. |
| [get_DeclaringType](./get_declaringtype/)() const | Bildiren türü alır. |
| [get_FullName](./get_fullname/)() const | Üyenin tam adını alır. Manuel olarak uygulanmış bölümlerde farklı olabilir. |
| virtual [get_MemberType](./get_membertype/)() const | Üyenin türünü gösteren bir [System::Reflection::MemberTypes](../membertypes/) değeri alır - yöntem, yapıcı, olay ve benzeri. |
| [get_Name](./get_name/)() const | Üye adını alır. |
| [get_ReflectedType](./get_reflectedtype/)() const | Yansıtılan tipin tipini alır. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Geçerli nesnenin temsil ettiği tipe uygulanan tüm özel öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
| [GetCustomAttributes](./getcustomattributes/)(bool) const | Geçerli nesnenin temsil ettiği tipe uygulanan tüm özel öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ObjectPtr](./objectptr/) | [Object](../../system/object/) nesnesine ortak gösterici için bir takma addır. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
