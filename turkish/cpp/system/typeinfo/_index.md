---
title: "System::TypeInfo sınıfı"
linktitle: "TypeInfo"
second_title: "Aspose.PUB için C++"
description: "System::TypeInfo sınıfı. C++'da belirli bir tipi temsil eder ve onun hakkında bilgi sağlar."
type: docs
weight: 6400
url: /tr/cpp/system/typeinfo/
---
## TypeInfo class


Belirli bir tipi temsil eder ve onun hakkında bilgi sağlar.

```cpp
class TypeInfo
```

## Nested classes

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Belirtilen özelliği tipin öznitelikler listesine ekler. |
| [AddDefaultConstructor](./adddefaultconstructor/)() | T tipinin varsayılan yapıcısını ayarlar. |
| [AddDefaultConstructor](./adddefaultconstructor/)(DefaultConstructor) | Sınıf örneği oluşturan fonktör aracılığıyla varsayılan yapıcıyı ayarlar. |
| [AddMember](./addmember/)(const SharedPtr\<System::Reflection::MemberInfo\>\&) | Belirtilen üyeyi tipin üyeler listesine ekler. |
| static [BoxedValueType](./boxedvaluetype/)() | Benzersiz bir [TypeInfo](./) yapısı, birden fazla Boxed* sınıfı tarafından paylaşılabilecek [BoxedValue](./boxedvalue/) tipi için sağlar. |
| [Equals](./equals/)(const TypeInfo\&) const |  |
| [get_Assembly](./get_assembly/)() const | UYGULANMADI. Geçerli nesne tarafından temsil edilen tipin tanımlandığı derlemeye bir gösterici döndürür. |
| [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | UYGULANMADI. Geçerli nesne tarafından temsil edilen tipin derleme adı dahil tam nitelikli adını döndürür. |
| [get_BaseType](./get_basetype/)() const | Temel tip tanımlayıcısını döndürür. |
| [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Geçerli Type nesnesinin, belirli tiplerle değiştirilmemiş tip parametrelerine sahip olup olmadığını gösteren bir değer alır. |
| [get_DeclaredMember](./get_declaredmember/)(const String\&) const | Belirtilen ada sahip üyelerin listesini alır. |
| [get_FullName](./get_fullname/)() const | Geçerli nesne tarafından temsil edilen tipin (derleme adı olmadan) tam nitelikli adını döndürür. |
| [get_GenericTypeArguments](./get_generictypearguments/)() const | Bu tip için jenerik tip argümanlarının bir dizisini alır. |
| [get_IsAbstract](./get_isabstract/)() const | Tipin soyut olup olmadığını ve geçersiz kılınması gerektiğini gösteren bir değer alır. |
| [get_IsArray](./get_isarray/)() const | Tipin bir dizi olup olmadığını gösteren bir değer alır. |
| [get_IsClass](./get_isclass/)() const | Tipin bir sınıf veya temsilci olup olmadığını gösteren bir değer alır; yani değer tipi ya da arayüz değildir. |
| [get_IsEnum](./get_isenum/)() const | Geçerli Type'ın bir enum (sayımlama) temsil edip etmediğini gösteren bir değer alır. |
| [get_IsGenericType](./get_isgenerictype/)() const |  |
| [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Geçerli Type'ın, diğer jenerik tiplerin oluşturulabileceği bir jenerik tip tanımı olup olmadığını gösteren bir değer alır. |
| [get_IsInterface](./get_isinterface/)() const | Tipin bir arayüz olup olmadığını gösteren bir değer alır; yani sınıf ya da değer tipi değildir. |
| [get_IsSealed](./get_issealed/)() const | Tipin sealed (kapalı) olarak ilan edilip edilmediğini gösteren bir değer alır. |
| [get_IsValueType](./get_isvaluetype/)() const | Tipin bir değer tipi olup olmadığını gösteren bir değer alır. |
| [get_IsVisible](./get_isvisible/)() const | Dernek dışındaki kod tarafından Type'in erişilip erişilemeyeceğini gösteren bir değer alır. |
| [get_Name](./get_name/)() const | Geçerli nesne tarafından temsil edilen tipin adını döndürür. |
| [get_Namespace](./get_namespace/)() const | Type'ın ad alanını alır. |
| [GetConstructor](./getconstructor/)(const ArrayPtr\<TypeInfo\>\&) const | Belirtilen dizideki tiplerle eşleşen parametrelere sahip bir genel örnek yapıcıyı arar. |
| [GetConstructors](./getconstructors/)(System::Reflection::BindingFlags) const | Belirtilen BindingFlags kullanılarak geçerli Type için tanımlı yapıcıları arar. |
| [GetConstructors](./getconstructors/)() const | Geçerli Type için tanımlı tüm genel yapıcıları döndürür. |
| [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&) const | Belirtilen tipe sahip ve geçerli nesne tarafından temsil edilen tipe uygulanmış özel özniteliği arar. |
| [GetCustomAttributes](./getcustomattributes/)() const | Tip'e uygulanan tüm özel öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Tip'e uygulanan belirli öznitelikleri temsil eden nesneleri içeren bir dizi döndürür. |
| [GetElementType](./getelementtype/)() const | UYGULANMADI. |
| [GetField](./getfield/)(const System::String\&, System::Reflection::BindingFlags) const | Belirtilen bağlama kısıtlamaları kullanılarak belirtilen alanı arar. |
| [GetFields](./getfields/)(System::Reflection::BindingFlags) const | Belirtilen bağlama kısıtlamaları kullanılarak geçerli Type için tanımlı alanları arar. |
| [GetGenericArguments](./getgenericarguments/)() const | Bu tip için jenerik tip argümanlarının bir dizisini alır. |
| [GetHashCode](./gethashcode/)() const | Bu örnek ile ilişkili bir karma kod döndürür. |
| [GetInterfaces](./getinterfaces/)() const | Geçerli Type tarafından uygulanmış veya miras alınmış tüm arabirimleri alır. |
| [GetMember](./getmember/)(const String\&) const | Belirtilen ada sahip üyelerin listesini alır. |
| [GetMethod](./getmethod/)(const String\&) const | Belirtilen ada sahip yöntemi alır. |
| [GetProperties](./getproperties/)() const | Geçerli Type'ın tüm genel özelliklerini döndürür. |
| [GetProperties](./getproperties/)(System::Reflection::BindingFlags) const | Belirtilen bağlama kısıtlamaları kullanılarak geçerli Type'ın özelliklerini arar. |
| [GetTemplParamType](./gettemplparamtype/)() const | Şablon parametre tipi tanımlayıcısını alır. |
| [Hash](./hash/)() const | Geçerli nesne tarafından temsil edilen tip ile ilişkili bir karma değer döndürür. |
| [IsAssignableFrom](./isassignablefrom/)(const TypeInfo\&) const | Belirtilen tipin bir örneğinin geçerli tipin değişkenine atanıp atanamayacağını belirler. |
| [IsDefined](./isdefined/)(const TypeInfo\&, bool) const | UYGULANMADI. Belirtilen tipin veya türetilmiş tiplerinin bir veya daha fazla özniteliğinin bu üye üzerine uygulanıp uygulanmadığını gösterir. |
| [IsInstanceOfType](./isinstanceoftype/)(const SharedPtr\<Object\>\&) const | Belirtilen nesnenin geçerli tipin bir örneği olup olmadığını belirler. |
| [IsSubclassOf](./issubclassof/)(const TypeInfo\&) const | Geçerli nesne tarafından temsil edilen tipin belirtilen sınıfın bir alt sınıfı olup olmadığını belirler. |
| [operator!=](./operator!=/)(const TypeInfo\&) const | Geçerli ve belirtilen [TypeInfo](./) nesnelerinin eşit olmaması durumunu belirler. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Geçerli [TypeInfo](./) nesnesinin null-nesne olmadığını, yani bir tip temsil ettiğini belirler. |
| [operator==](./operator==/)(const TypeInfo\&) const | Geçerli ve belirtilen [TypeInfo](./) nesnelerinin eşit olup olmadığını belirler. |
| [operator==](./operator==/)(std::nullptr_t) const | Geçerli [TypeInfo](./) nesnesinin null-nesne olup olmadığını belirler, yani herhangi bir türü temsil etmez. |
| [reset](./reset/)() | [TypeInfo](./) nesnesini null olarak ayarlar. |
| [set_IsValueType](./set_isvaluetype/)(bool) | Türün değer tipi olup olmadığını gösteren bir değeri ayarlar. |
| [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Temel tür tanımlayıcısını ayarlar. |
| [SetTemplParamType](./settemplparamtype/)(const TypeInfo\&) | Şablon parametresi tür tanımlayıcısını ayarlar. |
| static [StringHash](./stringhash/)(const char_t *) | Belirtilen dize için hash değerini hesaplar. |
| [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen türün adını içeren bir dize döndürür. |
| static [Type](./type/)() | [TypeInfo](./) sınıfını temsil eden bir [TypeInfo](./) nesnesi döndürür. |
| [TypeInfo](./typeinfo/)() | Varsayılan yapıcı (hiçbir tür ayarlanmamış). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Null nesne yapıcı (hiçbir tür ayarlanmamış). |
| [TypeInfo](./typeinfo/)(const char_t *) | Yapıcı. |
| [TypeInfo](./typeinfo/)(const char_t *, uint32_t) | Yapıcı. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Yapıcı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [EmptyType](./emptytype/) | [TypeInfo](./) boş listesini temsil eden sabit. |
| static [EmptyTypes](./emptytypes/) | [TypeInfo](./) boş listesini temsil eden sabit. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Türü oluşturmak için fonksiyon işaretçisi. |
## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
