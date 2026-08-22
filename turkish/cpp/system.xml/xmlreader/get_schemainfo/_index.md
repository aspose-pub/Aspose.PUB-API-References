---
title: "System::Xml::XmlReader::get_SchemaInfo yöntemi"
linktitle: "get_SchemaInfo"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlReader::get_SchemaInfo yöntemi. C++'ta şema doğrulaması sonucu geçerli düğüme atanmış şema bilgilerini döndürür."
type: docs
weight: 2200
url: /tr/cpp/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo method


Şema doğrulaması sonucunda geçerli düğüme atanmış şema bilgilerini döndürür.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### ReturnValue

Geçerli düğüm için şema bilgilerini içeren bir IXmlSchemaInfo nesnesi. [Schema](../../../system.xml.schema/) bilgisi öğelere, özniteliklere veya boş olmayan bir [XmlReader::get_ValueType](../get_valuetype/) değerine sahip metin düğümlerine ayarlanabilir. Geçerli düğüm yukarıdaki düğüm türlerinden biri değilse veya [XmlReader](../) örneği şema bilgisi raporlamıyorsa, bu yöntem **nullptr** döndürür. Bu yöntem bir [XmlTextReader](../../xmltextreader/) veya [XmlValidatingReader](../../xmlvalidatingreader/) nesnesinden çağrılırsa, bu yöntem her zaman **nullptr** döndürür. Bu [XmlReader](../) uygulamaları get_SchemaInfo yöntemi aracılığıyla şema bilgisi sunmaz.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
