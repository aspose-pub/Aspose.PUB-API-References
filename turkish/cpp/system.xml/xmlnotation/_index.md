---
title: "System::Xml::XmlNotation sınıfı"
linktitle: "XmlNotation"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNotation sınıfı. C++'de <!NOTATION... > gibi bir notasyon bildirimi temsil eder."
type: docs
weight: 2900
url: /tr/cpp/system.xml/xmlnotation/
---
## XmlNotation class


**<!NOTATION... >** gibi bir gösterim bildirimini temsil eder.

```cpp
class XmlNotation : public System::Xml::XmlNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Bu düğümün bir kopyasını oluşturur. Notasyon düğümleri kopyalanamaz. Bu yöntemi bir [XmlNotation](./) nesnesi üzerinde çağırmak bir istisna fırlatır. |
| [get_InnerXml](./get_innerxml/)() override | Bu düğümün çocuklarını temsil eden işaretlemeyi döndürür. |
| [get_IsReadOnly](./get_isreadonly/)() override | Düğümün yalnızca okunur olup olmadığını gösteren bir değer döndürür. |
| [get_LocalName](./get_localname/)() override | Geçerli düğümün adını, ad alanı ön eki olmadan döndürür. |
| [get_Name](./get_name/)() override | Geçerli düğümün adını döndürür. |
| [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [get_OuterXml](./get_outerxml/)() override | Bu düğüm ve tüm çocuklarını temsil eden işaretlemeyi döndürür. |
| [get_PublicId](./get_publicid/)() | Notasyon bildirimindeki genel tanımlayıcının değerini döndürür. |
| [get_SystemId](./get_systemid/)() | Notasyon bildirimindeki sistem tanımlayıcının değerini döndürür. |
| [set_InnerXml](./set_innerxml/)(String) override | Bu düğümün çocuklarını temsil eden işaretlemeyi ayarlar. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümün çocuklarını belirtilen [XmlWriter](../xmlwriter/) ile kaydeder. Bu yöntem [XmlNotation](./) düğümlerinde etkisizdir. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Belirtilen [XmlWriter](../xmlwriter/) ile düğümü kaydeder. Bu yöntem, [XmlNotation](./) düğümleri üzerinde hiçbir etki yapmaz. |
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
