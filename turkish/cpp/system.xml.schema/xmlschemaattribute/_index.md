---
title: "System::Xml::Schema::XmlSchemaAttribute class"
linktitle: "XmlSchemaAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaAttribute sınıfı. Dünya Çapında Ağ Konsorsiyumu (W3C) tarafından belirlenen XML Şemasındaki öznitelik öğesini temsil eder. Öznitelikler, diğer belge öğeleri için ek bilgi sağlar. Öznitelik etiketi, şema için bir belgenin öğesinin etiketleri arasında iç içe yer alır. XML belgesi, C++'da bir öğenin açılış etiketinde adlandırılmış öğeler olarak öznitelikleri gösterir."
type: docs
weight: 1100
url: /tr/cpp/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute class


XML [Schema](../) öğesinden **attribute** öğesini Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirtildiği gibi temsil eder. Öznitelikler, diğer belge öğeleri için ek bilgi sağlar. Öznitelik etiketi, şema için bir belgenin öğesinin etiketleri arasında iç içe yer alır. XML belgesi, bir öğenin açılış etiketinde adlandırılmış öğeler olarak öznitelikleri gösterir.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AttributeSchemaType](./get_attributeschematype/)() | Öznitelik değerinin [XmlSchemaAttribute::get_SchemaType](./get_schematype/) veya [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) değerine dayalı olarak öznitelik tipini temsil eden bir [XmlSchemaSimpleType](../xmlschemasimpletype/) nesnesi döndürür. |
| [get_AttributeType](./get_attributetype/)() | Derleme sonrası **AttributeType** değerinin yorumunu tutan, öznitelik değerinin [XmlSchemaAttribute::get_SchemaType](./get_schematype/) veya [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) değerine dayalı nesneyi döndürür. |
| [get_DefaultValue](./get_defaultvalue/)() | Öznitelik için varsayılan değeri döndürür. |
| [get_FixedValue](./get_fixedvalue/)() | Öznitelik için sabit değeri döndürür. |
| [get_Form](./get_form/)() | Öznitelik için formu döndürür. |
| [get_Name](./get_name/)() | Öznitelik adını döndürür. |
| [get_QualifiedName](./get_qualifiedname/)() | Öznitelik için nitelikli adı döndürür. |
| [get_RefName](./get_refname/)() | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) bildirilen bir öznitelik adını döndürür. |
| [get_SchemaType](./get_schematype/)() | Öznitelik tipini basit bir tipe döndürür. |
| [get_SchemaTypeName](./get_schematypename/)() | Bu şemada tanımlanan basit tipin adını (veya belirtilen ad alanı tarafından gösterilen başka bir şemada tanımlananı) döndürür. |
| [get_Use](./get_use/)() | Özelliğin nasıl kullanıldığına ilişkin bilgileri döndürür. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Özellik için varsayılan değeri ayarlar. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Özellik için sabit değeri ayarlar. |
| [set_Form](./set_form/)(XmlSchemaForm) | Özellik için formu ayarlar. |
| [set_Name](./set_name/)(const String\&) | Özelliğin adını ayarlar. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu şemada (veya belirtilen ad alanı tarafından gösterilen başka bir şemada) bildirilen bir özelliğin adını ayarlar. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Özellik tipini basit bir tipe ayarlar. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Bu şemada tanımlanan (veya belirtilen ad alanı tarafından gösterilen başka bir şemada tanımlanan) basit tipin adını ayarlar. |
| [set_Use](./set_use/)(XmlSchemaUse) | Özelliğin nasıl kullanıldığına ilişkin bilgileri ayarlar. |
| [XmlSchemaAttribute](./xmlschemaattribute/)() | Yeni bir [XmlSchemaAttribute](./) sınıf örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
