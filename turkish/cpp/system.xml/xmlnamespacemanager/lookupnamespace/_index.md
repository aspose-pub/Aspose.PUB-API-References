---
title: "System::Xml::XmlNamespaceManager::LookupNamespace yöntemi"
linktitle: "LookupNamespace"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNamespaceManager::LookupNamespace yöntemi. Belirtilen önek için ad alanı URI'sını C++'ta döndürür."
type: docs
weight: 800
url: /tr/cpp/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace method


Belirtilen önek için isim alanı URI'sını döndürür.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const String\& | Çözmek istediğiniz ad alanı URI'sına sahip önek. Varsayılan ad alanıyla eşleşmek için [String::Empty](../../../system/string/empty/) değerini geçirin. |

### ReturnValue

Eşlenmiş bir ad alanı yoksa **prefix** için ad alanı URI'sı veya **nullptr**. Döndürülen dize atomize edilmiştir. Atomize edilmiş dizeler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) sınıfına bakın.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
