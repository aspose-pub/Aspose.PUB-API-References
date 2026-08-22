---
title: "System::Xml::Serialization::XmlSerializer sınıfı"
linktitle: "XmlSerializer"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Serialization::XmlSerializer sınıfı. Nesneleri XML belgelerine serileştirir ve XML belgelerinden geri serileştirir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt (stack) üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirin."
type: docs
weight: 600
url: /tr/cpp/system.xml.serialization/xmlserializer/
---
## XmlSerializer class


Nesneleri XML belgelerine serileştirir ve XML belgelerinden geri serileştirir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek, yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class XmlSerializer : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [CanDeserialize](./candeserialize/)(System::SharedPtr\<XmlReader\>) | Belirli okuyucunun serileştirilebilir durumda olup olmadığını kontrol eder. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::Stream\>) | XML belgesini nesneye geri serileştirir. |
| [Deserialize](./deserialize/)(System::SharedPtr\<IO::TextReader\>) | XML belgesini nesneye geri serileştirir. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>) | XML belgesini nesneye geri serileştirir. |
| [Deserialize](./deserialize/)(System::SharedPtr\<XmlReader\>, String) | XML belgesini nesneye geri serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::Stream\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<IO::TextWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String) | Belgeyi XML'e serileştirir. |
| [Serialize](./serialize/)(System::SharedPtr\<XmlWriter\>, System::SharedPtr\<Object\>, System::SharedPtr\<XmlSerializerNamespaces\>, String, String) | Belgeyi XML'e serileştirir. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Kodlama ad alanı adı. |
| static [WsdlNamespace](./wsdlnamespace/) | RTTI. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | WSDL tipleri ad alanı adı. |
## Ayrıca Bakınız

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PUB for C++](../../)
