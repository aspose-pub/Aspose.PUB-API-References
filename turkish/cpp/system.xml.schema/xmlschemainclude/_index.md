---
title: "System::Xml::Schema::XmlSchemaInclude sınıfı"
linktitle: "XmlSchemaInclude"
second_title: "Aspose.PUB için C++"
description: "System::Xml::Schema::XmlSchemaInclude sınıfı. Dünya Çapında Ağ Konsorsiyumu (W3C) tarafından belirlenen XML Şeması'ndan include öğesini temsil eder. Bu sınıf, dış bir şemadan bildirim ve tanımlamaları dahil etmek için kullanılır. Dahil edilen bildirim ve tanımlamalar, C++ içinde kapsayan şemada işlenmek üzere kullanılabilir."
type: docs
weight: 3600
url: /tr/cpp/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude class


XML [Schema](../) üzerinden Dünya Çapında Ağ [Web](../../system.web/) Konsorsiyumu (W3C) tarafından belirlenen **include** öğesini temsil eder. Bu sınıf, dış bir şemadan bildirim ve tanımlamaları dahil etmek için kullanılır. Dahil edilen bildirim ve tanımlamalar, kapsayan şemada işlenmek üzere kullanılabilir.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Annotation](./get_annotation/)() | **annotation** değerini döndürür. |
| [set_Annotation](./set_annotation/)(const SharedPtr\<XmlSchemaAnnotation\>\&) | **annotation** değerini ayarlar. |
| [XmlSchemaInclude](./xmlschemainclude/)() | Yeni bir [XmlSchemaInclude](./) sınıf örneği başlatır. |
## Typedefs

| [Calendar](./calendar/) işaretçi türü. | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Class [XmlSchemaExternal](../xmlschemaexternal/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PUB for C++](../../)
