---
title: "System::Xml::XmlAttribute sınıfı"
linktitle: "XmlAttribute"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlAttribute sınıfı. Bir özniteliği temsil eder. Öznitelik için geçerli ve varsayılan değerler C++'da bir belge türü tanımı (DTD) veya şemada tanımlanır."
type: docs
weight: 600
url: /tr/cpp/system.xml/xmlattribute/
---
## XmlAttribute class


Bir özniteliği temsil eder. Öznitelik için geçerli ve varsayılan değerler bir belge türü tanımı (DTD) veya şemada tanımlanır.

```cpp
class XmlAttribute : public System::Xml::XmlNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AppendChild](./appendchild/)(SharedPtr\<XmlNode\>) override | Belirtilen düğümü bu düğümün alt düğüm listesine sonuna ekler. |
| [CloneNode](./clonenode/)(bool) override | Bu düğümün bir kopyasını oluşturur. |
| [get_BaseURI](./get_baseuri/)() override | Düğümün temel Evrensel Kaynak Tanımlayıcısını (URI) döndürür. |
| [get_LocalName](./get_localname/)() override | Düğümün yerel adını döndürür. |
| [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Bu düğümün ad alanı URI'sını döndürür. |
| [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Bu düğümün ait olduğu [XmlDocument](../xmldocument/) döndürür. |
| virtual [get_OwnerElement](./get_ownerelement/)() | Özniteliğin ait olduğu [XmlElement](../xmlelement/) öğesini döndürür. |
| [get_Prefix](./get_prefix/)() override | Bu düğümün ad alanı önekini döndürür. |
| [get_SchemaInfo](./get_schemainfo/)() override | Şema doğrulaması sonucunda bu düğüme atanmış post-schema-validation-infoset'i döndürür. |
| virtual [get_Specified](./get_specified/)() | Öznitelik değerinin açıkça ayarlanıp ayarlanmadığını gösteren bir değeri döndürür. |
| [get_Value](./get_value/)() override | Düğümün değerini döndürür. |
| [InsertAfter](./insertafter/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Belirtilen düğümü, belirtilen referans düğümünün hemen sonrasına ekler. |
| [InsertBefore](./insertbefore/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Belirtilen düğümü, belirtilen referans düğümünün hemen öncesine ekler. |
| [PrependChild](./prependchild/)(SharedPtr\<XmlNode\>) override | Belirtilen düğümü, bu düğümün alt düğüm listesine başa ekler. |
| [RemoveChild](./removechild/)(SharedPtr\<XmlNode\>) override | Belirtilen alt düğümü kaldırır. |
| [ReplaceChild](./replacechild/)(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) override | Belirtilen alt düğümü, belirtilen yeni alt düğümle değiştirir. |
| [set_InnerText](./set_innertext/)(String) override | Düğümün ve tüm alt öğelerinin birleştirilmiş değerlerini ayarlar. |
| [set_InnerXml](./set_innerxml/)(String) override | Öznitelik değerini ayarlar. |
| [set_Prefix](./set_prefix/)(String) override | Bu düğümün ad alanı önekini ayarlar. |
| [set_Value](./set_value/)(String) override | Düğümün değerini ayarlar. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümün tüm alt öğelerini belirtilen [XmlWriter](../xmlwriter/) aracına kaydeder. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümü belirtilen [XmlWriter](../xmlwriter/) aracına kaydeder. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
