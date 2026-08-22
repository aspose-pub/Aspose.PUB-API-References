---
title: "System::Xml::Schema::XmlSchema sınıfı"
linktitle: "XmlSchema"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchema sınıfı. Dünya Çapında Web Konsorsiyumu (W3C) ve C++'da belirtildiği gibi bir XML Şeması için bellek içi temsil."
type: docs
weight: 400
url: /tr/cpp/system.xml.schema/xmlschema/
---
## XmlSchema class


Bir XML [Schema](../) için bellek içi temsil, Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) ve [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/) tarafından belirtildiği gibi.

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Compile](./compile/)(ValidationEventHandler) | XML [Schema](../)[Object](../../system/object/) Modeli (SOM)'i doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir. |
| [Compile](./compile/)(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) | XML [Schema](../)[Object](../../system/object/) Modeli (SOM)'i doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir. |
| [get_AttributeFormDefault](./get_attributeformdefault/)() | Şemanın hedef ad alanında bildirilen öznitelikler için formu döndürür. |
| [get_AttributeGroups](./get_attributegroups/)() | Şemadaki tüm global öznitelik gruplarının şema derlemesi sonrası değerini döndürür. |
| [get_Attributes](./get_attributes/)() | Şemadaki tüm öznitelikler için şema derlemesi sonrası değeri döndürür. |
| [get_BlockDefault](./get_blockdefault/)() | Şemanın **targetNamespace**'indeki öğe ve karmaşık tiplerde **block** özniteliğinin varsayılan değerini ayarlayan **blockDefault** özniteliğini döndürür. |
| [get_ElementFormDefault](./get_elementformdefault/)() | Şemanın hedef ad alanında bildirilen öğeler için formu döndürür. |
| [get_Elements](./get_elements/)() | Şemadaki tüm öğeler için şema derlemesi sonrası değeri döndürür. |
| [get_FinalDefault](./get_finaldefault/)() | Şemanın hedef ad alanındaki öğe ve karmaşık tiplerde **final** özniteliğinin varsayılan değerini ayarlayan **finalDefault** özniteliğini döndürür. |
| [get_Groups](./get_groups/)() | Şemadaki tüm grupların şema derlemesi sonrası değerini döndürür. |
| [get_Id](./get_id/)() | String kimliğini döndürür. |
| [get_Includes](./get_includes/)() | Dahil edilen ve içe aktarılan şemaların koleksiyonunu döndürür. |
| [get_IsCompiled](./get_iscompiled/)() | Şemanın derlenip derlenmediğini gösterir. |
| [get_Items](./get_items/)() | Şemadaki şema öğelerinin koleksiyonunu döndürür ve **schema** öğesi düzeyinde yeni öğe türleri eklemek için kullanılır. |
| [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** öğesinin başvurduğu dosyadaki satır numarasını döndürür. |
| [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** öğesinin başvurduğu dosyadaki satır konumunu döndürür. |
| [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Bu şema nesnesiyle kullanılacak XmlSerializerNamespaces'i döndürür. |
| [get_Notations](./get_notations/)() | Şemadaki tüm notasyonlar için şema derlemesi sonrası değeri döndürür. |
| [get_Parent](../xmlschemaobject/get_parent/)() | Bu [XmlSchemaObject](../xmlschemaobject/) öğesinin üst öğesini döndürür. |
| [get_SchemaTypes](./get_schematypes/)() | Şemadaki tüm şema türleri için şema derlemesi sonrası değeri döndürür. |
| [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Şemayı yükleyen dosyanın kaynak konumunu döndürür. |
| [get_TargetNamespace](./get_targetnamespace/)() | Şema hedef ad alanının Uniform Resource Identifier (URI) değerini döndürür. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Şema hedef ad alanına ait olmayan nitelikli öznitelikleri döndürür. |
| [get_Version](./get_version/)() | Şemanın sürümünü döndürür. |
| static [Read](./read/)(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) | Sağlanan [IO::TextReader](../../system.io/textreader/) üzerinden bir XML [Schema](../) okur. |
| static [Read](./read/)(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) | Sağlanan akıştan bir XML [Schema](../) okur. |
| static [Read](./read/)(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) | Sağlanan [XmlReader](../../system.xml/xmlreader/) üzerinden bir XML [Schema](../) okur. |
| [set_AttributeFormDefault](./set_attributeformdefault/)(XmlSchemaForm) | Şemanın hedef ad alanında bildirilen öznitelikler için formu ayarlar. |
| [set_BlockDefault](./set_blockdefault/)(XmlSchemaDerivationMethod) | **blockDefault** özniteliğini ayarlar; bu, şemanın **targetNamespace** içindeki öğe ve karmaşık türlerdeki **block** özniteliğinin varsayılan değerini belirler. |
| [set_ElementFormDefault](./set_elementformdefault/)(XmlSchemaForm) | Şemanın hedef ad alanında bildirilen öğeler için formu ayarlar. |
| [set_FinalDefault](./set_finaldefault/)(XmlSchemaDerivationMethod) | **finalDefault** özniteliğini ayarlar; bu, şemanın hedef ad alanındaki öğe ve karmaşık türlerdeki **final** özniteliğinin varsayılan değerini belirler. |
| [set_Id](./set_id/)(const String\&) | Dize kimliğini ayarlar. |
| [set_LineNumber](../xmlschemaobject/set_linenumber/)(int32_t) | **schema** öğesinin başvurduğu dosyadaki satır numarasını ayarlar. |
| [set_LinePosition](../xmlschemaobject/set_lineposition/)(int32_t) | **schema** öğesinin başvurduğu dosyadaki satır konumunu ayarlar. |
| [set_Namespaces](../xmlschemaobject/set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Bu şema nesnesiyle kullanılacak XmlSerializerNamespaces'i ayarlar. |
| [set_Parent](../xmlschemaobject/set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Bu [XmlSchemaObject](../xmlschemaobject/) öğesinin üst öğesini ayarlar. |
| [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const String\&) | Şemayı yükleyen dosyanın kaynak konumunu ayarlar. |
| [set_TargetNamespace](./set_targetnamespace/)(const String\&) | Şemanın hedef ad alanının Uniform Resource Identifier (URI) değerini ayarlar. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Şema hedef ad alanına ait olmayan nitelikli öznitelikleri ayarlar. |
| [set_Version](./set_version/)(const String\&) | Şemanın sürümünü ayarlar. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&) | Sağlanan veri akışına XML [Schema](../) yazar. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Belirtilen [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) kullanarak sağlanan Stream'e XML [Schema](../) yazar. |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&) | Sağlanan [IO::TextWriter](../../system.io/textwriter/) üzerine XML [Schema](../) yazar. |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Sağlanan TextWriter'a XML [Schema](../) yazar. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&) | Sağlanan [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla XML [Schema](../) yazar. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Sağlanan [XmlWriter](../../system.xml/xmlwriter/) aracılığıyla XML [Schema](../) yazar. |
| [XmlSchema](./xmlschema/)() | [XmlSchema](./) sınıfının yeni bir örneğini başlatır. |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | XML şema örnek ad alanı. Bu alan sabittir. |
| static [Namespace](./namespace/) | XML şema ad alanı. Bu alan sabittir. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
