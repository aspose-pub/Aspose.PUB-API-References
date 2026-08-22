---
title: "System::ExceptionWrapper sınıfı"
linktitle: "ExceptionWrapper"
second_title: "Aspose.PUB için C++"
description: "System::ExceptionWrapper sınıfı. C++'da Exception sınıfından türetilen istisnaların sarmalayıcısını temsil eden şablon."
type: docs
weight: 2600
url: /tr/cpp/system/exceptionwrapper/
---
## ExceptionWrapper class


Exception sınıfından türetilen istisnaların sarmalayıcısını temsil eden şablon.

```cpp
template<typename T>class ExceptionWrapper
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Herhangi bir istisna temsil etmeyen [ExceptionWrapper](./) sınıfının null örneğini oluşturur. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionPtr\&) | Geçilen işaretçiyi içeren [ExceptionWrapper](./) sınıfının bir örneğini oluşturur. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionWrapper\&) | Kopya yapıcı. |
| [ExceptionWrapper](./exceptionwrapper/)(ExceptionWrapper\&&) | Taşıma yapıcı. |
| explicit [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Parametreleri Exception sınıfı yapıcılarına ileten ve yeni Exception sınıfı örneğini tutan akıllı işaretçi oluşturan yapıcı. |
| static [operator new](./operatornew/)(std::size_t) |  |
| static [operator new[]](./operatornew[]/)(std::size_t) |  |
| [operator SharedPtr< Object >](./operatorsharedptr_object_/)() | SharedPtr<Object>'a örtük dönüşüm operatörü |
| [operator->](./operator-_/)() const | Exception nesnesinin üyelerine erişim sağlar. |
| [operator=](./operator=/)(const ExceptionWrapper\&) | Atama operatörü. |
| [operator=](./operator=/)(ExceptionWrapper\&&) | Taşıma atama operatörü. |
| static [Type](./type/)() | Exception tipi için [System::TypeInfo](../typeinfo/) nesnesini almanın kısayolu. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Dönüştürme işlevleri için kullanılır. |
## Ayrıca Bakınız

* Namespace [System](../)
* Library [Aspose.PUB for C++](../../)
