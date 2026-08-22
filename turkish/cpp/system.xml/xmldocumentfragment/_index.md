---
title: "System::Xml::XmlDocumentFragment sınıfı"
linktitle: "XmlDocumentFragment"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlDocumentFragment sınıfı. C++'da ağaç ekleme işlemleri için yararlı olan hafif bir nesneyi temsil eder."
type: docs
weight: 1500
url: /tr/cpp/system.xml/xmldocumentfragment/
---
## XmlDocumentFragment class


Ağaç ekleme işlemleri için yararlı olan hafif bir nesneyi temsil eder.

```cpp
class XmlDocumentFragment : public System::Xml::XmlNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Bu düğümün bir kopyasını oluşturur. |
| [get_InnerXml](./get_innerxml/)() override | Bu düğümün çocuklarını temsil eden işaretlemeyi döndürür. |
| [get_LocalName](./get_localname/)() override | Düğümün yerel adını döndürür. |
| [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Bu düğümün ait olduğu [XmlDocument](../xmldocument/) döndürür. |
| [set_InnerXml](./set_innerxml/)(String) override | Bu düğümün çocuklarını temsil eden işaretlemeyi ayarlar. |
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
