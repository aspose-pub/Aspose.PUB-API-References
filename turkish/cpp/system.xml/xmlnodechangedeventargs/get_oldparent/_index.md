---
title: "System::Xml::XmlNodeChangedEventArgs::get_OldParent yöntemi"
linktitle: "get_OldParent"
second_title: "Aspose.PUB için C++"
description: "System::Xml::XmlNodeChangedEventArgs::get_OldParent yöntemi. İşlem başlamadan önce XmlNode::get_ParentNode değerini C++'da döndürür."
type: docs
weight: 600
url: /tr/cpp/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent method


İşlem başlamadan önce [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) değerini döndürür.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### ReturnValue

İşlem başlamadan önce **ParentNode** değeri. Düğümün bir ebeveyni yoksa bu yöntem **nullptr** döndürür. Öznitelik düğümleri için, bu yöntem [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) değerini döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PUB for C++](../../../)
