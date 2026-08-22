---
title: "System::Xml::Schema::XmlSchema::Compile yöntemi"
linktitle: "Compile"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchema::Compile yöntemi. XML SchemaObject Model (SOM)'i doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi C++'ta derleme sırasında gerçekleştirilir."
type: docs
weight: 200
url: /tr/cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


XML [Schema](../../)[Object](../../../system/object/) Modeli (SOM)'i doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | XML [Schema](../../) doğrulama hataları hakkında bilgi alan doğrulama olay işleyicisi. |

## Ayrıca Bakınız

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


XML [Schema](../../)[Object](../../../system/object/) Modeli (SOM)'i doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | XML [Schema](../../) doğrulama hataları hakkında bilgi alan doğrulama olay işleyicisi. |
| resolver | const SharedPtr\<XmlResolver\>\& | [XmlResolver](../../../system.xml/xmlresolver/) **include** ve **import** öğelerinde başvurulan ad alanlarını çözmek için kullanılır. |

## Ayrıca Bakınız

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PUB for C++](../../../)
