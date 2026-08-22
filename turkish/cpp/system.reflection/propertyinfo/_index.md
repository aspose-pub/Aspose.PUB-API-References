---
title: "System::Reflection::PropertyInfo sınıfı"
linktitle: "PropertyInfo"
second_title: "Aspose.PUB için C++"
description: "System::Reflection::PropertyInfo sınıfı. C++'ta özellik bilgilerini temsil eder."
type: docs
weight: 1000
url: /tr/cpp/system.reflection/propertyinfo/
---
## PropertyInfo class


Özellik bilgisini temsil eder.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Bu üyenin bir özellik olduğunu gösteren bir MemberTypes değerini alır. |
| [get_PropertyType](./get_propertytype/)() | Özellik tipini alır. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>) | Belirli bir nesneden özellik değerini alır. |
| [GetValue](./getvalue/)(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Belirli bir nesneden özellik değerini alır. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Yapılandırıcı. Yalnızca const getter içeren özellik. |
| [PropertyInfo](./propertyinfo/)(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) | Yapılandırıcı. Yalnızca non-const getter içeren özellik. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) | Yapıcı. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) | Yapılandırıcı. [Nullable](../../system/nullable/) ayarlayıcı ve getter içeren özellik. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) | Yapılandırıcı. Yalnızca const getter içeren [Nullable](../../system/nullable/) özellik. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) | Yapılandırıcı. Yalnızca getter içeren [Object](../../system/object/) özellik. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) | string özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) | Const getter içeren sınıftan string özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) | [Decimal](../../system/decimal/) özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) | Const getter içeren sınıftan [Decimal](../../system/decimal/) özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)()) | Boolean özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(bool), bool(ClassType::*)() const) | Const getter içeren sınıftan boolean özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) | int64_t özellik bilgisini oluşturur. |
| [PropertyInfo](./propertyinfo/)(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) | Const getter içeren sınıftan int64_t özellik bilgisini oluşturur. |
| [set_PropertyType](./set_propertytype/)(const TypeInfo\&) | Bu özelliğin tipini ayarlar. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) | Belirli bir nesneye özellik değerini ayarlar. |
| [SetValue](./setvalue/)(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) | Belirli bir nesneye özellik değerini ayarlar. |
## Ayrıca Bakınız

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PUB for C++](../../)
