---
title: "System::Security::Cryptography::Xml::XmlDsigExcC14NTransform sınıfı"
linktitle: "XmlDsigExcC14NTransform"
second_title: "Aspose.PUB için C++"
description: "System::Security::Cryptography::Xml::XmlDsigExcC14NTransform sınıfı. Yorum içermeyen dijital imza için özel C14N XML kanonikleştirme dönüşümünü temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi C++'ta fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1700
url: /tr/cpp/system.security.cryptography.xml/xmldsigexcc14ntransform/
---
## XmlDsigExcC14NTransform class


Yorum içermeyen dijital imza için özel C14N XML kanonikleştirme dönüşümünü temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) ya da new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class XmlDsigExcC14NTransform : public System::Security::Cryptography::Xml::Transform
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_InclusiveNamespacesPrefixList](./get_inclusivenamespacesprefixlist/)() |  |
| [get_InputTypes](./get_inputtypes/)() override |  |
| [get_OutputTypes](./get_outputtypes/)() override |  |
| [GetDigestedOutput](./getdigestedoutput/)(SharedPtr\<HashAlgorithm\>) override |  |
| [GetOutput](./getoutput/)() override |  |
| [GetOutput](./getoutput/)(const TypeInfo\&) override |  |
| [LoadInnerXml](./loadinnerxml/)(SharedPtr\<System::Xml::XmlNodeList\>) override |  |
| [LoadInput](./loadinput/)(SharedPtr\<Object\>) override |  |
| [set_InclusiveNamespacesPrefixList](./set_inclusivenamespacesprefixlist/)(String) |  |
| [XmlDsigExcC14NTransform](./xmldsigexcc14ntransform/)() |  |
| [XmlDsigExcC14NTransform](./xmldsigexcc14ntransform/)(bool) |  |
| [XmlDsigExcC14NTransform](./xmldsigexcc14ntransform/)(bool, String) |  |
## Ayrıca Bakınız

* Class [Transform](../transform/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PUB for C++](../../)
