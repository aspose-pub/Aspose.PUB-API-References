---
title: "System::Xml::Serialization::IXmlSerializable sınıfı"
linktitle: "IXmlSerializable"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Serialization::IXmlSerializable sınıfı. XML serileştirme ve geri serileştirme için özel biçimlendirme sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 100
url: /tr/cpp/system.xml.serialization/ixmlserializable/
---
## IXmlSerializable class


XML serileştirme ve geri serileştirme için özel biçimlendirme sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class IXmlSerializable : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [GetSchema](./getschema/)() | [WriteXml()](./writexml/) yöntemi tarafından döndürülen ve [ReadXml()](./readxml/) yöntemi tarafından kabul edilen nesnenin XML temsili hakkında bilgi veren bir XmlSchema nesnesi. |
| virtual [ReadXml](./readxml/)(System::SharedPtr\<System::Xml::XmlReader\>) | Nesneyi XML temsilinden ayrıştırır. |
| virtual [WriteXml](./writexml/)(System::SharedPtr\<System::Xml::XmlWriter\>) | Geçerli nesneyi XML temsiline serileştirir. |
| virtual [~IXmlSerializable](./~ixmlserializable/)() | Yıkıcı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PUB for C++](../../)
