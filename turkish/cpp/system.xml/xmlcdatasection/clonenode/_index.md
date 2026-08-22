---
title: "System::Xml::XmlCDataSection::CloneNode yöntemi"
linktitle: "CloneNode"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlCDataSection::CloneNode yöntemi. Bu düğümün bir kopyasını C++'ta oluşturur."
type: docs
weight: 100
url: /tr/cpp/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode method


Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derin | bool | **true** belirtilen düğümün alt ağacını özyinelemeli olarak kopyalamak için; **false** yalnızca düğümü kendisini kopyalamak için. CDATA düğümlerinin alt düğümleri olmadığı için, parametre ayarına bakılmaksızın, kopyalanan düğüm her zaman veri içeriğini içerir. |

### ReturnValue

Kopyalanan düğüm.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
