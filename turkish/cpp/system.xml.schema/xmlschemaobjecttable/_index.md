---
title: "System::Xml::Schema::XmlSchemaObjectTable sınıfı"
linktitle: "XmlSchemaObjectTable"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaObjectTable sınıfı. XmlSchema sınıfındaki (örneğin, Attributes, AttributeGroups, Elements vb.) içerilen öğeler için koleksiyonları C++'da sağlar."
type: docs
weight: 5300
url: /tr/cpp/system.xml.schema/xmlschemaobjecttable/
---
## XmlSchemaObjectTable class


İçerilen öğeler için koleksiyonları [XmlSchema](../xmlschema/) sınıfında (örneğin, Attributes, AttributeGroups, Elements vb.) sağlar.

```cpp
class XmlSchemaObjectTable : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<SharedPtr<System::Xml::XmlQualifiedName>, SharedPtr<System::Xml::Schema::XmlSchemaObject>>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Contains](./contains/)(const SharedPtr\<XmlQualifiedName\>\&) | Belirtilen nitelikli adın koleksiyonda bulunup bulunmadığını belirler. |
| [get_Count](./get_count/)() | [XmlSchemaObjectTable](./) içinde bulunan öğe sayısını döndürür. |
| [get_Names](./get_names/)() | [XmlSchemaObjectTable](./) içindeki tüm adlandırılmış öğelerin bir koleksiyonunu döndürür. |
| [get_Values](./get_values/)() | [XmlSchemaObjectTable](./) içindeki tüm öğelerin tüm değerlerinin bir koleksiyonunu döndürür. |
| [GetEnumerator](./getenumerator/)() override | [XmlSchemaObjectTable](./) üzerinden yineleme yapabilen bir enumerator döndürür. |
| [idx_get](./idx_get/)(const SharedPtr\<XmlQualifiedName\>\&) | Nitelikli ada göre belirtilen [XmlSchemaObjectTable](./) içindeki öğeyi döndürür. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
