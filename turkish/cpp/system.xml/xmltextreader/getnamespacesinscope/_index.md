---
title: "System::Xml::XmlTextReader::GetNamespacesInScope metodu"
linktitle: "GetNamespacesInScope"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlTextReader::GetNamespacesInScope metodu. C++'da şu anda kapsam içinde olan tüm ad alanlarını içeren bir koleksiyon döndürür."
type: docs
weight: 3400
url: /tr/cpp/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope method


Şu anda kapsam içinde olan tüm ad alanlarını içeren bir koleksiyon döndürür.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kapsam | XmlNamespaceScope | Bir XmlNamespaceScope değeri; döndürülecek ad alanı düğümlerinin türünü belirtir. |

### ReturnValue

Tüm mevcut kapsam içi ad alanlarını içeren bir IDictionary nesnesi. Okuyucu bir öğe üzerinde konumlandırılmamışsa, boş bir sözlük (ad alanı yok) döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
