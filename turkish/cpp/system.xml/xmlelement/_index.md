---
title: "System::Xml::XmlElement sınıfı"
linktitle: "XmlElement"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlElement sınıfı. C++'da bir öğeyi temsil eder."
type: docs
weight: 1700
url: /tr/cpp/system.xml/xmlelement/
---
## XmlElement class


Bir öğeyi temsil eder.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Bu düğümün bir kopyasını oluşturur. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Mevcut düğümün herhangi bir özniteliği olup olmadığını gösteren bir **bool** değer döndürür. |
| [get_InnerText](./get_innertext/)() override | Düğümün ve tüm alt öğelerinin birleştirilmiş değerlerini döndürür. |
| [get_InnerXml](./get_innerxml/)() override | Bu düğümün yalnızca alt öğelerini temsil eden işaretlemeyi döndürür. |
| [get_IsEmpty](./get_isempty/)() | Elemanın etiket biçimini döndürür. |
| [get_LocalName](./get_localname/)() override | Geçerli düğümün yerel adını döndürür. |
| [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Bu düğümün ad alanı URI'sını döndürür. |
| [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Bu düğümün ait olduğu [XmlDocument](../xmldocument/) döndürür. |
| [get_Prefix](./get_prefix/)() override | Bu düğümün ad alanı önekini döndürür. |
| [get_SchemaInfo](./get_schemainfo/)() override | Şema doğrulaması sonucunda bu düğüme atanmış post şema doğrulama bilgi kümesini döndürür. |
| virtual [GetAttribute](./getattribute/)(String) | Belirtilen adla özelliğin değerini döndürür. |
| virtual [GetAttribute](./getattribute/)(String, String) | Belirtilen yerel ad ve ad alanı URI'sına sahip özelliğin değerini döndürür. |
| virtual [GetAttributeNode](./getattributenode/)(String) | Belirtilen adla [XmlAttribute](../xmlattribute/) döndürür. |
| virtual [GetAttributeNode](./getattributenode/)(String, String) | Belirtilen yerel ad ve ad alanı URI'sına sahip [XmlAttribute](../xmlattribute/) döndürür. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Belirtilen [XmlElement::get_Name](./get_name/) ile eşleşen tüm alt öğelerin listesini içeren bir [XmlNodeList](../xmlnodelist/) döndürür. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Belirtilen [XmlElement::get_LocalName](./get_localname/) ve [XmlElement::get_NamespaceURI](./get_namespaceuri/) değerleriyle eşleşen tüm alt öğelerin listesini içeren bir [XmlNodeList](../xmlnodelist/) döndürür. |
| virtual [HasAttribute](./hasattribute/)(String) | Geçerli düğümün belirtilen adla bir özelliği olup olmadığını belirler. |
| virtual [HasAttribute](./hasattribute/)(String, String) | Geçerli düğümün belirtilen yerel ad ve ad alanı URI'sına sahip bir özelliği olup olmadığını belirler. |
| [RemoveAll](./removeall/)() override | Geçerli düğümün belirtilen tüm özelliklerini ve alt öğelerini kaldırır. Varsayılan özellikler kaldırılmaz. |
| virtual [RemoveAllAttributes](./removeallattributes/)() | Elemandan belirtilen tüm özellikleri kaldırır. Varsayılan özellikler kaldırılmaz. |
| virtual [RemoveAttribute](./removeattribute/)(String) | Bir özelliği adla kaldırır. |
| virtual [RemoveAttribute](./removeattribute/)(String, String) | Belirtilen yerel ad ve ad alanı URI'sına sahip bir özelliği kaldırır. (Kaldırılan özelliğin varsayılan bir değeri varsa, hemen yerine konur). |
| virtual [RemoveAttributeAt](./removeattributeat/)(int32_t) | Elemandan belirtilen indeksli özellik düğümünü kaldırır. (Kaldırılan özelliğin varsayılan bir değeri varsa, hemen yerine konur). |
| virtual [RemoveAttributeNode](./removeattributenode/)(SharedPtr\<XmlAttribute\>) | Belirtilen [XmlAttribute](../xmlattribute/) kaldırır. |
| virtual [RemoveAttributeNode](./removeattributenode/)(String, String) | Yerel ad ve ad alanı URI'sı ile belirtilen [XmlAttribute](../xmlattribute/) kaldırır. (Kaldırılan özelliğin varsayılan bir değeri varsa, hemen yerine konur). |
| [set_InnerText](./set_innertext/)(String) override | Düğümün ve tüm alt öğelerinin birleştirilmiş değerlerini ayarlar. |
| [set_InnerXml](./set_innerxml/)(String) override | Bu düğümün yalnızca alt öğelerini temsil eden işaretlemeyi ayarlar. |
| [set_IsEmpty](./set_isempty/)(bool) | Elemanın etiket biçimini ayarlar. |
| [set_Prefix](./set_prefix/)(String) override | Bu düğümün ad alanı önekini ayarlar. |
| virtual [SetAttribute](./setattribute/)(String, String) | Belirtilen adla özniteliğin değerini ayarlar. |
| virtual [SetAttribute](./setattribute/)(String, String, String) | Belirtilen yerel ad ve ad alanı URI'siyle özniteliğin değerini ayarlar. |
| virtual [SetAttributeNode](./setattributenode/)(SharedPtr\<XmlAttribute\>) | Belirtilen [XmlAttribute](../xmlattribute/) ekler. |
| virtual [SetAttributeNode](./setattributenode/)(String, String) | Belirtilen [XmlAttribute](../xmlattribute/) ekler. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümün tüm alt öğelerini belirtilen [XmlWriter](../xmlwriter/) aracına kaydeder. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Geçerli düğümü belirtilen [XmlWriter](../xmlwriter/) ile kaydeder. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
