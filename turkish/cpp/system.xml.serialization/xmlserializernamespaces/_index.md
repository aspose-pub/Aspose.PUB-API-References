---
title: "System::Xml::Serialization::XmlSerializerNamespaces sınıfı"
linktitle: "XmlSerializerNamespaces"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Serialization::XmlSerializerNamespaces sınıfı. C++'ta bir XML belge örneğinde nitelikli adlar oluşturmak için Serialization::XmlSerializer'ın kullandığı XML ad alanları ve öneklerini içerir."
type: docs
weight: 800
url: /tr/cpp/system.xml.serialization/xmlserializernamespaces/
---
## XmlSerializerNamespaces class


[Serialization::XmlSerializer](../xmlserializer/) tarafından bir XML belge örneğinde nitelikli adlar oluşturmak için kullanılan XML ad alanları ve öneklerini içerir.

```cpp
class XmlSerializerNamespaces : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Bir [Serialization::XmlSerializerNamespaces](./) nesnesine bir önek ve ad alanı çifti ekler. |
| [get_Count](./get_count/)() | Koleksiyondaki önek ve ad alanı çiftlerinin sayısını döndürür. |
| [get_NamespaceList](./get_namespacelist/)() |  |
| [get_Namespaces](./get_namespaces/)() |  |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<Collections::Generic::Dictionary\<String, String\>\>\&) |  |
| [ToArray](./toarray/)() | Bir [Serialization::XmlSerializerNamespaces](./) nesnesindeki önek ve ad alanı çiftlerinin dizisini döndürür. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)() | [Serialization::XmlSerializerNamespaces](./) sınıfının yeni bir örneğini başlatır. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const SharedPtr\<XmlSerializerNamespaces\>\&) | Belirtilen önek ve ad alanı çifti koleksiyonunu içeren **[XmlSerializerNamespaces](./)** örneğini kullanarak [Serialization::XmlSerializerNamespaces](./) sınıfının yeni bir örneğini başlatır. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | [Serialization::XmlSerializerNamespaces](./) sınıfının yeni bir örneğini başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PUB for C++](../../)
