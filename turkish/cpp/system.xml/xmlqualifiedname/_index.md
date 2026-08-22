---
title: "System::Xml::XmlQualifiedName sınıf"
linktitle: "XmlQualifiedName"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlQualifiedName sınıfı. C++'ta bir XML nitelikli adını temsil eder."
type: docs
weight: 3200
url: /tr/cpp/system.xml/xmlqualifiedname/
---
## XmlQualifiedName class


XML nitelikli bir adı temsil eder.

```cpp
class XmlQualifiedName : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Belirtilen [XmlQualifiedName](./) nesnesinin mevcut [XmlQualifiedName](./) nesnesine eşit olup olmadığını belirler. |
| [get_IsEmpty](./get_isempty/)() const | [XmlQualifiedName](./) nesnesinin boş olup olmadığını gösteren bir değer döndürür. |
| [get_Name](./get_name/)() const | [XmlQualifiedName](./) nitelikli adının dize temsili döndürülür. |
| [get_Namespace](./get_namespace/)() const | [XmlQualifiedName](./) ad alanının dize temsili döndürülür. |
| [GetHashCode](./gethashcode/)() const override | [XmlQualifiedName](./) için hash kodunu döndürür. |
| static [ToString](./tostring/)(const String\&, const String\&) | [XmlQualifiedName](./) nesnesinin dize değerini döndürür. |
| [ToString](./tostring/)() const override | [XmlQualifiedName](./) nesnesinin dize değerini döndürür. |
| [XmlQualifiedName](./xmlqualifiedname/)() | [XmlQualifiedName](./) sınıfının yeni bir örneğini başlatır. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&) | Belirtilen adla [XmlQualifiedName](./) sınıfının yeni bir örneğini başlatır. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&, const String\&) | Belirtilen ad ve ad alanı ile [XmlQualifiedName](./) sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Boş bir [XmlQualifiedName](./) sağlar. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
