---
title: "System::Reflection ad alanı"
linktitle: "System::Reflection"
second_title: "Aspose.PUB için C++"
description: "C++'ta System::Reflection ad alanını nasıl kullanılır."
type: docs
weight: 3300
url: /tr/cpp/system.reflection/
---



## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) sınıfı, derlemeyi tanımlar. Destek sınırlıdır çünkü kurallar C# ve C++ arasında oldukça farklıdır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [AssemblyName](./assemblyname/) | Derleme adını tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Çalışan derlemede tipi kaydetmek için Singleton. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Çalışan derlemede tipi kaydetmek için tekil nesnelerin temel tipi. |
| [ConstructorInfo](./constructorinfo/) | Yapıcı meta verilerine erişim sağlar. |
| [FieldInfo](./fieldinfo/) | Bir alanın özniteliklerini keşfeder ve alan meta verilerine erişim sağlar. |
| [MemberInfo](./memberinfo/) | Üyeler hakkında yansıma bilgisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [MethodBase](./methodbase/) | Yöntem hakkında temel bilgi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [MethodInfo](./methodinfo/) | Sınıf yöntemi hakkında bilgiyi temsil eder. |
| [PropertyInfo](./propertyinfo/) | Özellik bilgisini temsil eder. |
## Enums

| Enum | Açıklama |
| --- | --- |
| [BindingFlags](./bindingflags/) | Üyeleri ve tipleri arama modlarını ve bağlamalarını tanımlar. |
| [FieldAttributes](./fieldattributes/) | Yansıtılan alan öznitelikleri. |
| [MemberTypes](./membertypes/) | Her üye türünü işaretler. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException, bir modüldeki sınıflardan herhangi biri yüklenemezse Module.GetTypes yöntemi tarafından fırlatılır. ReflectionTypeLoadException sınıfı örneklerini asla [System::SmartPtr](../system/smartptr/) içine sarmayın. |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException, yansıma yoluyla çağrılan yöntemler tarafından fırlatılır. TargetInvocationException sınıfı örneklerini asla [System::SmartPtr](../system/smartptr/) içine sarmayın. |
