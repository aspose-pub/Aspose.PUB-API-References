---
title: "System::Xml::XmlNamedNodeMap sınıfı"
linktitle: "XmlNamedNodeMap"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNamedNodeMap sınıfı. C++'da ad veya indeks ile erişilebilen düğüm koleksiyonunu temsil eder."
type: docs
weight: 2200
url: /tr/cpp/system.xml/xmlnamednodemap/
---
## XmlNamedNodeMap class


İsim veya indeks ile erişilebilen bir düğüm koleksiyonunu temsil eder.

```cpp
class XmlNamedNodeMap : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [begin](./begin/)() const | Koleksiyonun ilk öğesine bir yineleyici alır. |
| [cbegin](./cbegin/)() const | Koleksiyonun ilk öğesine bir yineleyici alır. |
| [cend](./cend/)() const | Koleksiyonun son öğesinin arkasındaki mevcut olmayan bir öğe için yineleyici alır. |
| [end](./end/)() const | Koleksiyonun son öğesinin arkasındaki mevcut olmayan bir öğe için yineleyici alır. |
| virtual [get_Count](./get_count/)() | [XmlNamedNodeMap](./) içindeki düğüm sayısını döndürür. |
| [GetEnumerator](./getenumerator/)() override | [XmlNamedNodeMap](./) içindeki düğüm koleksiyonu üzerinde yineleme desteği sağlar. |
| virtual [GetNamedItem](./getnameditem/)(String) | İsimle belirtilen bir [XmlNode](../xmlnode/) alır. |
| virtual [GetNamedItem](./getnameditem/)(String, String) | Eşleşen [XmlNode::get_LocalName](../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) değerlerine sahip bir düğüm alır. |
| virtual [Item](./item/)(int32_t) | [XmlNamedNodeMap](./) içinde belirtilen indeksdeki düğümü alır. |
| virtual [RemoveNamedItem](./removenameditem/)(String) | Düğümü [XmlNamedNodeMap](./) içinden kaldırır. |
| virtual [RemoveNamedItem](./removenameditem/)(String, String) | Eşleşen [XmlNode::get_LocalName](../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) değerlerine sahip bir düğümü kaldırır. |
| virtual [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) | [XmlNode::get_Name](../xmlnode/get_name/) değerini kullanarak bir [XmlNode](../xmlnode/) ekler. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [iterator](./iterator/) | Yineleyici türü. |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PUB for C++](../../)
