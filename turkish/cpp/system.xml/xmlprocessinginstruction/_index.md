---
title: "System::Xml::XmlProcessingInstruction sınıfı"
linktitle: "XmlProcessingInstruction"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlProcessingInstruction sınıfı. C++'da XML'in belge metninde işlemciye özgü bilgileri tutmak için tanımladığı bir işleme talimatını temsil eder."
type: docs
weight: 3100
url: /tr/cpp/system.xml/xmlprocessinginstruction/
---
## XmlProcessingInstruction class


XML'in belge metninde işlemciye özgü bilgileri tutmak için tanımladığı bir işleme talimatını temsil eder.

```cpp
class XmlProcessingInstruction : public System::Xml::XmlLinkedNode
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Bu düğümün bir kopyasını oluşturur. |
| [get_Data](./get_data/)() | Hedefi hariç tutarak işleme talimatının içeriğini döndürür. |
| [get_InnerText](./get_innertext/)() override | Düğümün ve tüm alt öğelerinin birleştirilmiş değerlerini döndürür. |
| [get_LocalName](./get_localname/)() override | Düğümün yerel adını döndürür. |
| [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [get_Target](./get_target/)() | İşleme talimatının hedefini döndürür. |
| [get_Value](./get_value/)() override | Düğümün değerini döndürür. |
| [set_Data](./set_data/)(const String\&) | Hedefi hariç tutarak işleme talimatının içeriğini ayarlar. |
| [set_InnerText](./set_innertext/)(String) override | Düğümün ve tüm alt öğelerinin birleştirilmiş değerlerini ayarlar. |
| [set_Value](./set_value/)(String) override | Düğümün değerini ayarlar. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümün tüm alt öğelerini belirtilen [XmlWriter](../xmlwriter/)'a kaydeder. ProcessingInstruction düğümlerinin alt öğesi olmadığı için bu yöntemin bir etkisi yoktur. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Düğümü belirtilen [XmlWriter](../xmlwriter/) aracına kaydeder. |
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
